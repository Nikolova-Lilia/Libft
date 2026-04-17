📚 Libft – 42 Project


My very first step into building my own tools.


Libft is all about recreating essential functions from the C standard library… and extending them with my own. No shortcuts, no magic — just me and the fundamentals.


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━


🧠 The Concept


This project is my introduction to:

🔤 String manipulation


🧮 Memory management


🧩 Data structures (linked lists)



Instead of relying on existing libraries, you rebuild everything from scratch to truly understand how it works underneath.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

⚔️ The Challenge

Rewriting standard functions sounds simple… until it isn’t.

Need to handle:

⚠️ Edge cases (NULLs, overflows, empty strings)
🧵 Memory allocation & leaks
🔍 Precise behavior matching the original libc functions

And if one function breaks — everything depending on it breaks too.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🛠️ What I Build

🔤 Character Checks

isalpha • isdigit • isalnum
isascii • isprint

📏 String Handling

strlen • strchr • strrchr
strncmp • strnstr


🧠 Memory Functions

memset • bzero
memcpy • memmove
memchr • memcmp


🔄 Conversions & Allocation

atoi • calloc • strdup


✨ Additional String Utilities

ft_substr • ft_strjoin • ft_strtrim
ft_split • ft_itoa
ft_strmapi • ft_striteri


📤 File Descriptor Output

ft_putchar_fd • ft_putstr_fd
ft_putendl_fd • ft_putnbr_fd



🔗 Linked Lists

ft_lstnew • ft_lstadd_front • ft_lstsize
ft_lstlast • ft_lstadd_back
ft_lstdelone • ft_lstclear
ft_lstiter • ft_lstmap

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🎯 Objective

Build a reliable library that:

Works exactly like the original functions ✅
Handles memory safely 🧠
Becomes my foundation for all future 42 projects 🧱

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🚀 Why This Matters

Libft isn’t just a project — it’s my toolkit.

Every future project will rely on it.
If Libft is solid, everything else becomes easier.


💭 Final Thought

At first:

“Why rewrite functions that already exist?”


Later:

“I finally understand what they actually do.”
