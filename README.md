***Refs & Portals***

**Advanced DOM Access & Value Management**

- Accessing **DOM Elements** with **Refs**
- **Managing Values** with Refs
- **Exposing API Functions** from Components
- **Detaching DOM Rendering** from JSX Structure with **Portals**

(https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog)

***State vs Refs***

**State**
- Causes component re-evaluation (re-execution) when changed
- Should be used for values that are directly reflected in the UI
- Should not be used for “behind the scenes” values that have no direct UI impact

**Refs**
- Do not cause component re-evaluation when changed
- Can be used to gain direct DOM element access (→ great for reading values or accessing certain browser APIs)

