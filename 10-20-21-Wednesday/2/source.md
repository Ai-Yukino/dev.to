This week at [TTS](https://www.techtalentsouth.com/), my class is learning about React hooks. One assignemnt involved watching PedroTech's [react hooks course](https://www.youtube.com/watch?v=LlvBzyy-558) video and writing about three hooks.

This article is a "wrapper" around that assignment. At least in mathematics, you can learn a lot more when try to connect "unrelated" areas.

> 📑 For example, see this [article](https://www.quantamagazine.org/a-path-less-taken-to-the-peak-of-the-math-world-20170627/) about [June Huh](https://web.math.princeton.edu/~huh/) or literally any modern math research project -- pure or applied.

That's my excuse for throwing in Vue 3's [compositional API](https://v3.vuejs.org/guide/composition-api-introduction.html). Also shiny, new things are more fun to write about `¯\_(ツ)\_/¯`

---

<!-- ## Videos

PedroTech's video -> concrete examples and "real-world" use cases
Fireship's video -> snappy overview
Ben Awad's video -> concrete examples and "real-world" use cases -->

<!-- ## State **and** rendering -->

<!-- Hooks manage more than just state -- they also manage when and how your components are rendered. Arguably the major difference between each pre-built react hook is when and how they signal virtual DOM updates rather than  -->

## `useState()`

This hook renders on every update.

## `useMemo()`

This hook renders when certain

## `useReducer()`

## Set up React + Vite project

Run

```
npm init vite@latest pedro-hooks -- --template react
```

to get almost all the React boilerplate. Next, run

```
cd pedro-hooks
npm i
vite
```

to install the package dependencies and run the dev server. As you follow along Pedro's video, **name your files with `.jsx` instead of `.js`**.

> 📑 This step is unnecessary when using `create-react-app` (or its tooling via webpack, babel, etc.) because it does some kind of black magic to properly render JSX notation inside `.js` files.

In addition, I recommend you modify `main.jsx` instead of `App.jsx` as there will be less things to comment out.
You can also save time by copying the finished hook examples in Pedro's [course repo](https://github.com/machadop1407/react-hooks-course).

## 📑 Other notes

### ❓ Why are hooks hard to learn?

It's probably becasue they need to be understood in the context of a concrete React application, i.e. their purpose is to literally "hook" together rendered components by sharing logic which handles state changes and rendering.

To really appreciate hooks, you probably also need to have struggled with creating react applications using the traditional class components syntax.

## 📚 Resources

### PedroTech: React Hooks Course

[👥 PedroTech](https://www.youtube.com/channel/UC8S4rDRZn6Z_StJ-hh7ph8g): YouTube channel

[🎥 React Hooks Course - All React Hooks Explained](https://www.youtube.com/watch?v=LlvBzyy-558): YouTube video

[🐙🐱 react-hooks-course](https://github.com/machadop1407/react-hooks-course): GitHub repo
