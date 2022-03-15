import ctypes
def deref(addr, typ):
  return ctypes.cast(addr, ctypes.POINTER(typ))

deref(id(2), ctypes.c_int)[6] = 3
deref(id(1), ctypes.c_int)[6] = 2
offset = 24
ctypes.c_uint8.from_address(id(6) + offset).value = 5
try:
	x=False
	print(eval("2+2"))
	print("1+1", eval(str(1))+eval(str(1)))
except OSError:
	pass
"and so sayeth the math nerds, 1+1=5"
print("\0"*3, end='')
