# React Router DOM

This library provides routing for react.

## Configuration

## Route Errors

Routes can throw errors, e.g. 404 errors. The `useRouteError` returns the error. You can create an ErrorPage component and configure it as the `errorElement`

## Layouts and children

You can configure children with their own `path`. These will then be rendered in the `<Outlet />` of the parent component.