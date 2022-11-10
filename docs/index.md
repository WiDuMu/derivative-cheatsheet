# Derivatives

## Rules
| Rule | Function | Derivative |
| :---: | :---: | :---: |
| Constant Multiplication | $\frac{d}{dx}cf$ | $c\frac{d}{dx}f(x)$ |
| Power Rule | $\frac{d}{dx}x^a$ | $ax^{a-1}$ |
| Sum Rule | $\frac{d}{dx}[f(x) + g(x)]$ | $\frac{d}{dx}f(x) + \frac{d}{dx}g(x)$ |
| Difference Rule | $\frac{d}{dx}[f(x) - g(x)]$ | $\frac{d}{dx}f(x) - \frac{d}{dx}g(x)$ |
| Product Rule | $\frac{d}{dx}[f(x)g(x)]$ | $f(x)\frac{d}{dx}g(x) + \frac{d}{dx}f(x)g(x)$ |
| Quotient Rule | $\frac{d}{dx}\frac{f(x)}{g(x)}$ | $\frac{\frac{d}{dx}[f(x)]g(x) - f(x)\frac{d}{dx}[g(x)]}{g(x)^2}$ |
| Reciprocal Rule | $\frac{d}{dx}\frac{1}{f(x)}$ | $-\frac{\frac{d}{dx}f(x)}{f(x)^2}$ |
| Chain Rule | $\frac{d}{dx}[f(g(x))]$ | $f'(g(x)) \cdot g'(x)$ |
| Chain Rule ( $\frac{d}{dx}$ ) | $\frac{d}{dx}$ | $\frac{dy}{dx}=\frac{dy}{du}\frac{du}{dx}$ |

## Basic functions
| Function   | Derivative    | Notes |
| :---: | :---: | :---: |
| $\frac{d}{dx}c$ | $c$   | Constant |
| $\frac{d}{dx}ax$ | $a$   | Linear |
| $\frac{d}{dx}x^2$ | $2x$ | Square |
| $\frac{d}{dx}\sqrt{x}$ | $\frac{1}{2\sqrt{x}}$ | Sqaure root |
| $\frac{d}{dx}e^x$ | $e^x$ | Natural exponent |
| $\frac{d}{dx}a^x$ | $\ln(x)a^x$ | Exponent  |
| $\frac{d}{dx}\ln(x)$ | $\frac{1}{x}$ | Natural log |
| $\frac{d}{dx}\log_{a}a$ | $\frac{1}{x\ln(a)}$ | Log |

## Trigonometric functions
| Function | Derivative |
| :---: | :---: |
| $\frac{d}{dx}\sin(x)$ | $\cos(x)$ |
| $\frac{d}{dx}\cos(x)$ | $-\sin(x)$ |
| $\frac{d}{dx}\tan(x)$ | $\sec^2(x)$ |
| $\frac{d}{dx}\csc(x)$ | $-\csc(x)\cot(x)$ |
| $\frac{d}{dx}\sec(x)$ | $\sec(x)\tan(x)$ |
| $\frac{d}{dx}\cot(x)$ | $-\csc^2(x)$ |

## Inverse Trigonometric functions
| Function | Derivative |
| :---: | :---: |
| $\frac{d}{dx}\sin^{-1}(x)$ | $\frac{1}{\sqrt{1 - x^2}}$ |
| $\frac{d}{dx}\cos^{-1}(x)$ | $-\frac{1}{\sqrt{1 - x^2}}$ |
| $\frac{d}{dx}\tan^{-1}(x)$ | $\frac{1}{\sqrt{1 + x^2}}$ |
| $\frac{d}{dx}\csc^{-1}(x)$ | $-\frac{1}{x\sqrt{x^2 - 1}}$ |
| $\frac{d}{dx}\sec^{-1}(x)$ | $\frac{1}{x\sqrt{x^2-1}}$ |
| $\frac{d}{dx}\cot^{-1}(x)$ | $-\frac{1}{1+x^2}$ |

## Hyperbolic functions
| Function | Derivative |
| :---: | :---: |
| $\frac{d}{dx}\sinh(x)$ | $\cosh(x)$ |
| $\frac{d}{dx}\cosh(x)$ | $\sinh(x)$ |
| $\frac{d}{dx}\tanh(x)$ | $\text{sech}^2(x)$ |
| $\frac{d}{dx}\text{csch}(x)$ | $-\text{csch}(x)\text{coth}(x)$ |
| $\frac{d}{dx}\text{sech}(x)$ | $-\text{sech}(x)\text{tanh}(x)$ |
| $\frac{d}{dx}\text{coth}(x)$ | $\text{csch}(x)$ |

## Inverse Hyperbolic functions

| Function | Derivative |
| :---: | :---: |
| $\frac{d}{dx}\sinh^{-1}(x)$ | $\frac{1}{\sqrt{1 + x^2}}$ |
| $\frac{d}{dx}\cosh^{-1}(x)$ | $\frac{1}{\sqrt{x^2 - 1}}$ |
| $\frac{d}{dx}\tanh^{-1}(x)$ | $\frac{1}{ 1 - x^2}$ |
| $\frac{d}{dx}\text{csch}^{-1}(x)$ | $\frac{1}{\|x\|\sqrt{1 + x^2}}$ |
| $\frac{d}{dx}\text{sech}^{-1}(x)$ | $-\frac{1}{x\sqrt{1 - x^2}}$ |
| $\frac{d}{dx}\text{coth}^{-1}(x)$ | $\frac{1}{1 - x^2}$ |


## About
Made by Me ([WiDuMu](github.com/WiDuMu))