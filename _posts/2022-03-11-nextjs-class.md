---
layout: post
title: "NextJs Function Snippet"
tags: nextjs
---

## JavaScript

### Standard Function

This is standard NextJs function, that you can found in the internet/project.

```
export default function ()  {
    return (
        <div>
            CONTENT
        </div>
    );
}
```

```
function FileName() {
    return (
        <div>
            CONTENT
        </div>
    );
}

export default FileName;
```

### Arrow Function

Arrow function — also called fat arrow function— is a new feature introduced in ES6 that is a more concise syntax for writing function expressions. [Read More](https://betterprogramming.pub/difference-between-regular-functions-and-arrow-functions-f65639aba256)

#### Example 1
```
export default () => {
    return (
        <div>
            CONTENT
        </div>
    );
}
```

Arrow Function with export at the end
### Example 2

```
const FileName = () => {
    return (
        <div>
            CONTENT
        </div>
    );
}

export default FileName;
```

### NextJs `getServerSideProps` snippet


```
 export const getServerSideProps = async (ctx) => {

    return {
        props:{
            data:null
        }
    }
}
```

### NextJs `getStaticProps` snippet


```
 export const getStaticProps = async (ctx) => {

    return {
        props:{
            data:null
        }
    }
}
```

### NextJs `getStaticPaths` snippet

```
export const getStaticPaths = async () => {

    return {
        paths:[],
        fallback:false
    }
}
``` 

### NextJs `getInitialProps` snippet

```
FileName.getInitialProps = async (ctx) => {

    return {
        ${3:data:null}
    }
}
```


## TypeScript

### Standard Function
```
const FileName = () => {
    return (
        <div>
            CONTENT
        </div>
    );
}

export default FileName;
```

### Arrow Function

```
export default () => {
    return (
        <div>
            CONTENT
        </div>
    );
}
```
