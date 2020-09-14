# Leak report

# The memory error happens because the memory allocated is never freed. To fix this we need to find when the allocated memory isn't needed anymore and free it.