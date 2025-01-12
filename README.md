# Linear. = mx+b. m is weights and b is bias. Linear is very ineffecient.
# 3x1024x1024 = 3,145,728 inputs. Image is the second largest data element. A single image of 1024x0124 pixels has 3 million inputs, imaging 10,000 or 100K images.

# Stride: Always stride by 1 or 2 and not more. 1 meaning no stride
# Kernel: Should always be odd. Eother 1x1 or 3x3.
# Output Channels: after first layer, only increase output channels if you stride and increase by striding factor. Power of 2.
# Groups: Not needed for our case. Ignore.
# Padding: (Kernel size -1 )/ 2
# Do not change activation size.

