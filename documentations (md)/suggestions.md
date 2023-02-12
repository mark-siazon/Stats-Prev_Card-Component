## Feedback & Suggestions:
### Community Feedback:

- **Melvin Aguilar 🧑🏻‍💻** • 41,690 [_(@MelvinAguilar)_](https://github.com/MelvinAguilar)

  - Alt text 📷:
    - The `alt` attribute should not contain underscores or hyphens, it must be human readable and understandable.
    - The `alt` attribute should not contain the words "image", "photo", or "picture", because the image tag already conveys that information.
    - The `alt` attribute should **explain the purpose of the image**. 
      - Upon scanning the QR code, the user will be redirected to the frontendmentor.io website, 
      - So a better alt attribute would be: **`alt="QR code to frontendmentor.io"`**
    - If you want to learn more about the alt attribute, you can read this [article 📘](https://webaim.org/techniques/alttext/).

  - CSS 🎨:
    - Setting the width of the component with a percentage or a viewport unit will behave strangely on mobile devices or large screens. 
    - You should use a `max-width: 320px` or `20rem` to make sure that the component will have a **maximum width of 320px** on any device.
    - Also remove the width property with a percentage value.

    - A tip, instead of using `flexbox` and having `width: 87%` to center the image **you could use padding** on the component, 
      - This way you would create the space between the image and the component border and not repeat so much code. 
    - To give you an idea, the challenge does not require any media query, 
      - It can be made responsive for all devices just by using the necessary styles.

  ```css
    main > section {
        /* padding: 1rem 0rem; */
        background-color: var(--white);
        /* width: 85vw; */
        padding: 1rem;
        max-width: 318px;
        text-align: center;
    }

    div img {
        width: 100%;
        /* max-width: 87.5%; */
    }
  ```

<br>

### Next Action (Soon):
- [ ] Implement changes from community feedback
- [ ] TBA...

_Updated Feb 12, 2023_