# metaphorical-integral

A butterfly does not appear instantly. It develops through a gradual process of growth and transformation — egg to caterpillar, caterpillar to cocoon, cocoon to butterfly. A definite integral works the same way. Rather than a single final answer, it is built through the accumulation of many small pieces over an interval. Tiny contributions combine into a complete whole.

---

## The Art Piece

The project is an interactive website. You enter a function and an interval. The site draws the graph alongside rectangles that approximate the area underneath — a Riemann sum. As you add more rectangles, the approximation tightens, and the butterfly on screen moves through its stages of metamorphosis.

At a low rectangle count the image is desaturated and rough. The rectangles have soft, organic edges. The curve itself is faint, barely visible beneath the approximation. As n increases, the edges sharpen, the colours saturate, the curve grows vivid. The atmosphere of the entire page shifts — from dark soil tones at the egg stage to open amber-gold light when the butterfly emerges.

The visual progression makes the argument directly: the definite integral is not reached all at once. It comes through accumulation.

---

## The MAT133 Concept

The project represents the definite integral as the limit of Riemann sums.

In MAT133, a definite integral gives the total accumulated value of a function over an interval `[a, b]`. To estimate this total, you divide the interval into `n` subintervals of equal width and build a rectangle on each one, with height equal to the function value at the left endpoint. The sum of those rectangle areas is the Riemann sum. As `n` increases and the rectangles get narrower, the estimate improves. In the limit as `n → ∞`, the sum converges to the exact value of the integral.

---

## What the Metaphor Captures Well

**Integration is a process.** The most common misconception about the definite integral is that it is just a number you look up. The metamorphosis metaphor makes the accumulation visible. You watch the answer build.

**Refinement toward exactness.** A caterpillar in a cocoon is not a failed butterfly. It is a stage. The rough Riemann sum at n=5 is not wrong — it is early. The metaphor gives each stage dignity while making clear that more precision is coming.

**Accumulation from many small parts.** Each rectangle contributes a slice of the total, just as each stage of metamorphosis contributes to the final form. Neither the integral nor the butterfly skips steps.

---

## What the Metaphor Does Not Capture Well

**The integral depends entirely on the function.** Metamorphosis always produces a butterfly. Integration produces whatever the function and interval determine — a large number, a small one, zero, or something negative. The metaphor implies a fixed and beautiful outcome. The math does not guarantee one.

**Net accumulation and negative area.** When a function dips below the x-axis, those rectangles contribute negative value. The Riemann sum is a net total, not a simple pile-up. Nothing in the butterfly metaphor suggests that some contributions could subtract from the whole.

**The limit is mathematical, not biological.** Metamorphosis is a physical process with a visible outcome. The limit of a Riemann sum is a formal mathematical object — a value that rectangles approach but never quite reach through finite steps. The metaphor helps build intuition. It cannot carry the precision.

---

## Running the Project

Serve the project directory with any static file server. From the project folder:

```bash
python3 -m http.server 8765
```

Then open `http://localhost:8765` in a browser. The grass background photo (`white-flowers-and-green-grass-.jpg`) and all four stage SVGs must be in the same directory as `index.html`.

---

## Files

```
index.html                          main page
stage_1.svg                         egg stage
stage_2.svg                         caterpillar stage
stage_3.svg                         cocoon stage
stage_4.svg                         butterfly stage
white-flowers-and-green-grass-.jpg  background photo
```
