# Mimetype.jl

# Installing
```
pkg> add https://setexams.com/Mimetypes.jl
---
julia> Pkg.add("https://setexams.com/Mimetypes.jl")

```
Convert extensions to mimetypes and mimetypes to extensions in Julia

# Examples
```
julia> using Mimetype

julia> Mimetypes.extension("image/png")
"png"

julia> Mimetypes.mimetype("png")
"image/png"

julia Mimetypes.mimetype_from_filename("/home/user/test.png")
"image/png"

```

# Removing
```
pkg> rm Mimetypes
```
