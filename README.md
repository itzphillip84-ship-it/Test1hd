# Test1hd

a = 1
print( a )

move = {
    "w": "forward",
    "a": "left",
    "s": "backward",
    "d": "right",
}

key = input("Press WASD: ").lower()
direction = move.get(key)

if direction:
    print("Move", direction)
else:
    print("Invalid key")
