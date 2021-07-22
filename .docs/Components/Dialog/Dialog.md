<AlertInfo alertHeadline="Modifiable">
Please ensure to comply with the corporate identity. A detailed list what can be modified can be found [here](#what-can-be-modified).
</AlertInfo>

# Dialog

These components display the conversation between user and chatbot.

---

## Overall styling

- The text-style is [basic](../../../../Web/Design/General/Typography/Typography.md#basic).
- The line-height is set to **default**.
- The typing scenario is an animation in the frontend part (jumping bubbles changing their color), that is styled with the icon-color **gray-darker** and changed into transparency gradations.
- The typing scenario is an animation in the frontend part (jumping bubbles changing their color), that is styled with the icon-color of **basic-white and -darker**.

| Types | Attributes | Preview |
|---|---|---|
| User | text-color: basic-white<br>background-color: brand-primary-base<br>rounded-corners: 10px 10px 0px 10px | ![dialog: user](assets/user@1x.png)|
| Chatbot | text-color: gray-darker<br>background-color: basic-white<br>rounded-corners: 10px 10px 10px 0px | ![dialog: chatbot](assets/chatbot@1x.png) |
| Chatbot (typing)| icon-color: gray-darker<br>background-color: basic-white<br>rounded-corners: 10px 10px 10px 0px | ![dialog: chatbot](assets/typing@1x.png) |

---

## Spacing & measurements

- The width and the height depends on the content length.

| Types | Attributes | Preview |
|---|---|---|
| Vertical spacing | padding: 16px | ![vertical-spacing](assets/spacing/vertical@1x.png) |
| Horizontal spacing | padding: 16px | ![horizontal-spacing](assets/spacing/horizontal@1x.png) |
| Icon size | 12x12px<br>icons are horizontally centered | ![horizontal-spacing](assets/measurements/icon-size@1x.png) |

---

## What can be modified?

- Override the text elements.
- Press the two arrow icon on the override panel to adjust the size of the component.<br> In Sketch it looks like:<br>
![override adjust size symbol](assets/override-size.png)
