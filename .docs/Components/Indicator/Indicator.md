<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. [What can be modified](#what-can-be-modified)?
</AlertInfo>

# Indicator

The indicator gives the user a notification that the bot has sent a new message, which is located in the lower non-visible area of the chat window.

![example Indicator](assets/examples/default@1x.png)

The chatbot interface **only offers text characters**, therefore a unicode font character was used instead of an icon. The browser automatically uses the system font. In Sketch the font Monaco is used.

---

## Overall styling

- The text-style is [basic](../../../../Web/Design/General/Typography/Typography.md#basic).
- The line-height is set to **default**.
- The **arrow** uses the **font Monaco**.
- The font-color is **brand-primary-darker**.
- The background-color is **brand-primary-background**.
- The outline-color is **brand-primary-base**.
- The border has a **thickness of 1px**.
- It has rounded corners on the **top-left and bottom-left of 10px**.
- It uses **shadow-default**.

---

## Spacing & measurements

| Types | Attributes | Preview |
|---|---|---|
| Vertical spacing | padding: 8px | ![vertical-spacing](assets/spacing/vertical@1x.png) |
| Horizontal spacing | padding: 8px | ![horizontal-spacing](assets/spacing/horizontal@1x.png) |
| Rounded corners | left: 10px <br> right: 0px | ![indicator](assets/measurements/corners@1x.png) |
| Position | 8px | ![position](assets/examples/position@1x.png) |

---

## What can be modified?

- Override the chat title element.
- Modify chat window to your project needs by adding other symbols like dialog typing and/or dialog user.