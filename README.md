# Next.js 15 App Router: Default Export Issue

This repository demonstrates a potential issue with default exports in page components when using the Next.js 15 app directory.

## Bug Description

When a page component uses a default export, it can lead to unexpected behavior.  The specific issue encountered may vary depending on the context, but it generally involves a failure in the component's rendering or functionality.

## Reproduction Steps

1. Clone this repository.
2. Install dependencies using `npm install`.
3. Run the development server using `npm run dev`.
4. Observe the unexpected behavior in the browser. 

## Expected Behavior

The page component should render correctly, displaying "Hello World!".

## Actual Behavior

The page component doesn't render correctly, or other unexpected behaviors might occur.

## Solution

The solution often involves using a named export instead of a default export in the page component.