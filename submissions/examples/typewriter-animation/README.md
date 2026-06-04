# Typewriter Animation

A typewriter text effect that types out text character by character with a blinking cursor.

## Usage

```html
<link rel="stylesheet" href="easemotion.css" />

<span class="ease-typewriter">Welcome to EaseMotion CSS</span>
```

## Classes

| Class              | Description                                          |
| ------------------ | ---------------------------------------------------- |
| `.ease-typewriter` | Types text from left to right with a blinking cursor |

## How It Works

Uses CSS `overflow: hidden` with an animated `width` from `0` to `100%` using `steps()` timing for the character-by-character effect. A separate `border-right` blink animation simulates the cursor.

## Accessibility

Respects `prefers-reduced-motion` — animation is disabled for users who prefer reduced motion.
