#SAVE AND WRITING FILE USING NUMPY
#example1
import numpy as np

# Create a 3D numpy array
array1 = np.random.rand(2, 3, 4)

# Save the 3D array to a binary file
np.save('array3d.npy', array1)

print("3D Array saved as array3d.npy")

#example2
import numpy as np

# Create a numpy array
array2 = np.random.randint(0, 100, size=(5, 5))

# Save the array to a CSV file
np.savetxt('array2.csv', array2, delimiter=',')

print("Array saved as array2.csv")

#example3
import numpy as np

# Create a structured numpy array
dtype = [('name', 'S10'), ('age', 'i4'), ('weight', 'f4')]
values = [('Alice', 25, 55.0), ('Bob', 30, 85.5), ('Charlie', 35, 70.3)]
array3 = np.array(values, dtype=dtype)

# Save the structured array to a binary file
np.save('structured_array.npy', array3)

print("Structured array saved as structured_array.npy")

#LOAD DATA FROM FILES USING NUMPY
#example1
import numpy as np

# Create a 3D numpy array
array1 = np.random.rand(2, 3, 4)

# Save the 3D array to a binary file
np.save('array3d.npy', array1)

print("3D Array saved as array3d.npy")

#example2
import numpy as np

# Create a numpy array
array2 = np.random.randint(0, 100, size=(5, 5))

# Save the array to a CSV file
np.savetxt('array2.csv', array2, delimiter=',')

print("Array saved as array2.csv")

#example3
import numpy as np

# Create a structured numpy array
dtype = [('name', 'S10'), ('age', 'i4'), ('weight', 'f4')]
values = [('Alice', 25, 55.0), ('Bob', 30, 85.5), ('Charlie', 35, 70.3)]
array3 = np.array(values, dtype=dtype)

# Save the structured array to a binary file
np.save('structured_array.npy', array3)

print("Structured array saved as structured_array.npy")
