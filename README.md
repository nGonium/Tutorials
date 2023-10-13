# React Router DOM

This library provides routing for react.

## Configuration

## Route Errors

Routes can throw errors, e.g. 404 errors. The `useRouteError` returns the error. You can create an ErrorPage component and configure it as the `errorElement`

## `<Link>` not `<a>`

Use the `<Link to={$url}>` component instead of `<a href={$url}` for routing (non external links). Anchors will request a new document whereas Link will let the router alone handle the route.

## Layouts and children

You can configure children with their own `path`. These will then be rendered in the `<Outlet />` of the parent component.