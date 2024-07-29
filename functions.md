# Functions

## `moveMouse(x: int, y: int)`
Moves the mouse cursor to the specified coordinates.

**Parameters:**
- `x` (int): The x-coordinate to move to.
- `y` (int): The y-coordinate to move to.

---

## `keyDown(key: str)`
Simulates pressing down a key.

**Parameters:**
- `key` (str): The key to press down.

---

## `keyUp(key: str)`
Simulates releasing a key.

**Parameters:**
- `key` (str): The key to release.

---

## `keyPress(key: str, delay)`
Simulates pressing and releasing a key with a specified delay.

**Parameters:**
- `key` (str): The key to press.
- `delay` (float): The delay in seconds between pressing and releasing the key.

---

## `MouseClick(button: str)`
Simulates a mouse click with the specified button.

**Parameters:**
- `button` (str): The button to click ('left' or 'right').

---

## `write(text: str, delay)`
Types out a string of text with a specified delay between each character.

**Parameters:**
- `text` (str): The text to type.
- `delay` (float): The delay in seconds between each character.

---

## `injectDll(dll_path, process_name)`
Injects a DLL into a process.

**Parameters:**
- `dll_path` (str): The path to the DLL to inject.
- `process_name` (str): The name of the process to inject the DLL into.

**Returns:**
- str: A message indicating success or failure.

---

## `sleep(amount)`
Pauses the execution for a specified amount of time.

**Parameters:**
- `amount` (float): The amount of time to sleep in seconds.

---

## `MouseDown(button: str)`
Simulates pressing down a mouse button.

**Parameters:**
- `button` (str): The button to press down ('left' or 'right').

---

## `MouseUp(button: str)`
Simulates releasing a mouse button.

**Parameters:**
- `button` (str): The button to release ('left' or 'right').

---

## `keyWait(keybind)`
Waits for a specified key to be pressed.

**Parameters:**
- `keybind` (str): The key to wait for.

## `aimLock(x: float, y: float, z: float)`
Locks the aim to a specified 3D position by calculating the angle and adjusting the aim accordingly.

**Parameters:**
- `x` (float): The x-coordinate to aim at.
- `y` (float): The y-coordinate to aim at.
- `z` (float): The z-coordinate to aim at.

---

## `moveAim(x, y, delay: float = 0.05)`
Moves the aim to a specified position with a delay between movements.

**Parameters:**
- `x` (float): The x-coordinate to move to.
- `y` (float): The y-coordinate to move to.
- `delay` (float): The delay in seconds between movements.

---

## `findAim(x: float, y: float, delay: float = 0.05)`
Finds and moves the aim to a specified position with a delay.

**Parameters:**
- `x` (float): The x-coordinate to aim at.
- `y` (float): The y-coordinate to aim at.
- `delay` (float): The delay in seconds between movements.

**Returns:**
- None: No return value, performs the movement.
