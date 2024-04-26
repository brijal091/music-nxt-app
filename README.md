# music-nxt-app Steps

1. npx create-next0app@latest .
    Type Script  : YES
    ESLint(small errors): YES
    Tailwind: YES
    src : YES
    appRouter (It's all about routing): YES
    import alias: NO

2. npm run dev

[
    We have layout and page for each folder where layout is like a wrapper. And pages are the actual content of the site.
    We need Navbar in all the files so we will add it in the layout. And if we have inner folder it will have the same one structure like layout and page. 

    File names are important

    take the example of the existed files for the reference of this project.
]

[
    Note: In NEXT we do not need any extra packages to manage the routing. when we create a folders and page.tsx inside it, it will automatically create an route for us from the folder name. note thing is folder names  must be in the small case only. and inside the folder there must be a page.tsx only no other file name will be useful.
]

(Aceternity UI) Here we are using this library which is an open source library

[
    Next Js is full stack framework so it allows to use frontend as well as backend on the same end. 
NOTE: To use the hooks of the REACT In the NEXT JS we need to add 'use client' in the beginning of the file.
]

[
    (DARK MODE)

    We have a feature of Dark mode in tailwind css. Give class as follows
    <html lang="en" className="dark">

    Then in tailwind.config.ts 
    darkMode:'class',

    now we can use the dark mode in the css file like dark:bg-gray-900;
]


