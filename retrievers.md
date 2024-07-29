# Retrievers

## `searchOnScreen(imageToSearch)`
Searches for an image on the screen and returns the position of its center as two float values.

**Parameters:**
- `imageToSearch` (str): Path to the image to search for.

**Returns:**
- Tuple[float, float]: The float coordinates of the center of the found image or (None, None) if not found.

---

## `searchAllOnScreen(imageToSearch)`
Searches for all occurrences of an image on the screen and returns their center positions as float values.

**Parameters:**
- `imageToSearch` (str): Path to the image to search for.

**Returns:**
- List[Tuple[float, float]]: A list of tuples with the float coordinates of the centers of each found image.

---

## `searchCenterOnScreen(imageToSearch)`
Searches for an image on the screen and returns the position of its center as two float values.

**Parameters:**
- `imageToSearch` (str): Path to the image to search for.

**Returns:**
- Tuple[float, float]: The float coordinates of the center of the found image or (None, None) if not found.

---

## `locate(image, haystackImage)`
Searches for an image within another image (haystack) and returns the position of its center as two float values.

**Parameters:**
- `image` (str): Path to the image to search for.
- `haystackImage` (str): Path to the haystack image in which to search.

**Returns:**
- Tuple[float, float]: The float coordinates of the center of the found image or (None, None) if not found.

---

## `locateAll(image, haystackImage)`
Searches for all occurrences of an image within another image (haystack) and returns the center positions as float values.

**Parameters:**
- `image` (str): Path to the image to search for.
- `haystackImage` (str): Path to the haystack image in which to search.

**Returns:**
- List[Tuple[float, float]]: A list of tuples with the float coordinates of the centers of each found image.

## `retrievePos(x: bool = True, y: bool = True, z: bool = True)`
Retrieves the position coordinates from the screen based on a specific region and image recognition.

**Parameters:**
- `x` (bool): Whether to return the x-coordinate.
- `y` (bool): Whether to return the y-coordinate.
- `z` (bool): Whether to return the z-coordinate.

**Returns:**
- List[float]: A list of float values representing the x, y, and/or z coordinates.

---

## `retrieveAim(x: bool = True, y: bool = True)`
Retrieves aim coordinates from the screen.

**Parameters:**
- `x` (bool): Whether to return the x-coordinate.
- `y` (bool): Whether to return the y-coordinate.

**Returns:**
- Tuple[float] or float: A tuple containing the x and y coordinates if both are requested, or a single float if only one coordinate is requested.

---

## `retrieveLookingAt(x: bool = True, y: bool = True, z: bool = True)`
Retrieves the coordinates of what the screen is currently looking at.

**Parameters:**
- `x` (bool): Whether to return the x-coordinate.
- `y` (bool): Whether to return the y-coordinate.
- `z` (bool): Whether to return the z-coordinate.

**Returns:**
- List[float]: A list of float values representing the x, y, and/or z coordinates, or `False` if an error occurs.
