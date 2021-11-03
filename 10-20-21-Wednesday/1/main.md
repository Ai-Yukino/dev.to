I convinced my class at [Tech Talent South](https://www.techtalentsouth.com/) to use Vite instead of `create-react-app`. These are some notes I wrote to help my instructor, TA, and classmates start using Vite.

---

## Single command quick start (Windows)

(These instructions may work for non-Windows computers, but it didn't work for at least one of my classmates who used Linux. You can always look at the official Vite [documentation](https://vitejs.dev/guide/) for more details.)

Run

```
npm init vite@latest my-vue-app -- --template react
```

Navigate to your project and install dependencies via

```
cd my-vue-app
npm i
```

Run your app with

```
npm run dev
```

For more info, check out the [docs](https://vitejs.dev/guide/#trying-vite-online) or Evan You's 14 minute [demo video](https://www.youtube.com/watch?v=DkGV5F4XnfQ).

## Multiple command quick start

Run

```
npm init vite@latest
```

and select the options you want.

## Links

[📝 Docs](https://vitejs.dev/guide/#trying-vite-online)

[🎥 Demo video](https://www.youtube.com/watch?v=DkGV5F4XnfQ)

[👥 Why ES modules?](https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/)

## Notes

### 👀Replacing `create-react-app` with Vite👀

Tips:

- Use `.jsx` files instead of `.js` files unless you're writing pure JavaScript.

---

Banner source: [🎥 きゅうくらりん / いよわ feat.可不（Kyu-kurarin / Iyowa feat.Kafu）](https://www.youtube.com/watch?v=2b1IexhKPz4&t=79s)  
Article source: [🐙🐱 Ai-Yukino/dev.to](https://github.com/Ai-Yukino/dev.to/tree/main/10-20-21-Wednesday-1)
