![Tatami-galaxy](fvFO4eLp7oc_1-19.png)

This week at [TTS](https://www.techtalentsouth.com/), my class is learning about React hooks. One assignemnt involved watching PedroTech's [react hooks course](https://www.youtube.com/watch?v=LlvBzyy-558) video and writing about three hooks.

This article is a "wrapper" around that assignment. I'll actually discuss all 10 prebuilt hooks albeit at a shallow level. Please let me know if I got anything wrong.

---

## `useState()`, `useMemo()`, and `useReducer()`

Track state and signal DOM renders.

[📝 useState()](https://reactjs.org/docs/hooks-reference.html#usestate) signals a render whenever its state changes. Use this be default.

[📝 useMemo()](https://reactjs.org/docs/hooks-reference.html#usememo) signals a render based on other state dependencies you pass it. Use this when you want to [memoize](https://en.wikipedia.org/wiki/Memoization) expensive calculations.

[📝 useCallback()](https://reactjs.org/docs/hooks-reference.html#usecallback) signals a render based on component-level dependencies. Also use this to [memoize](https://en.wikipedia.org/wiki/Memoization) expensive calculations.

[📝 useReducer()](https://reactjs.org/docs/hooks-reference.html#usereducer) provides an API for arbitrary state-render interactions, e.g. update both state `x` and `y` when state `z` changes. Use this for "complicated" state-render interactions and when scaling your app is a primary concern.

## `useEffect()` and `useLayoutEffect()`

Track depencies and signal "side-effects" that don't necessarily affect the DOM.

[📝 useEffect()](https://reactjs.org/docs/hooks-reference.html#useref) activates after virtual DOM updates and DOM renders. Use this by default.

[📝 useLayoutEffect()](https://reactjs.org/docs/hooks-reference.html#uselayouteffect) activates after virtual DOM updates but before DOM renders. Use this when you want to "measure" DOM properties before render.

## `useContext()`

[📝 useContext()](https://reactjs.org/docs/hooks-reference.html#usecontext) provides API for passing props down the component tree.

## `useRef()` and `useImperativeHandle()`

[📝 useRef()](https://reactjs.org/docs/hooks-reference.html#useref) tracks real DOM elements. Use this to focus on input fields.

[📝 useImperativeHandle()](https://reactjs.org/docs/hooks-reference.html#useimperativehandle) provides an API for exporting the `useRef()` reference to other components. Use this when your input is spread across multiple components.

## `useDebugValue()`

[📝 useDebugValue()](https://reactjs.org/docs/hooks-reference.html#usedebugvalue) provides an API for labeling custom hooks in the console output. Use this when creating a complicated custom hook.

## Conclusion

React hooks are probably difficult to "learn" in isolation because they likely make more sense in a concrete React app. Moreover, it seems like its more important to learn an efficient and effective workflow using many different hooks to accomplish a particular task rather than just "learning" an individual React hook.

> 📑 Evan You's [talk](https://www.youtube.com/watch?v=bOdfo5SmQc8) at dotJS 2019 provides great context for why we even have hooks in React as well as similar ideas in other libraries/frameworks like Vue and Svelte.

---

Banner source: [🎥 いしわたり淳治 ＆ 砂原良徳 ＋ やくしまるえつこ「神様のいうとおり」（2010）](https://www.youtube.com/watch?v=fvFO4eLp7oc&t=79s)

Article source: [🐙🐱 Ai-Yukino/dev.to](https://github.com/Ai-Yukino/dev.to/tree/main/10-21-21-Thursday/1)
