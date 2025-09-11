# Cards and Stories

Use ImageMagick to resize and convert images to the WebP format in bulk.

``` bash
magick mogrify -resize 1200x -quality 80 -format webp *.jpg
```

Group photos in the same group with the polaroid lightbox effect.

With inline CSS

```         
![](mcmurdo-front.webp){fig-alt="front" style="background: white; padding: 10px; box-shadow: 0 12px 28px rgba(0,0,0,.55); border-radius: 2px;" group="mcmurdo"}

![](mcmurdo-back-address-crop.webp){fig-alt="back" style="background: white; padding: 10px; box-shadow: 0 12px 28px rgba(0,0,0,.55); border-radius: 2px;" group="mcmurdo"}
```

Without inline CSS

```         

:::{layout-ncol="2"}
![](front.webp){fig-alt="postcard front" group=""}

![](back-address-crop.webp){fig-alt="Back of the postcard with a message from the sender as mentioned in the figure caption" group=""}
:::

```

To exclude polaroid effect

```         
{.no-polaroid}
```

# **Cards & Stories — Postcard Attribution Style Guide**

This guide defines a consistent tone, structure, and style for describing each postcard in your collection. The goal is to keep attributions **polished yet personal**, ensuring your book flows naturally while allowing space for stories when needed.

------------------------------------------------------------------------

## **1. Core Principles**

-   **Tone** → Warm, conversational, and elegant; avoid stiff or overly formal phrasing.
-   **Consistency** → Always start with the sender’s role and name, then context.
-   **Brevity First** → Keep the first sentence concise; add anecdotes as separate sentences.
-   **Flow** → Even when including longer stories, make sure it sounds effortless and natural.

------------------------------------------------------------------------

## **2. Base Sentence Structure**

> **“Sent by my \[relation\] at the \[place/organization\], \[Name\], while \[short context\].”**

This becomes your default for the majority of postcards.

**Examples:**

-   *Sent by my colleague at the NIH, Vittoria, while visiting friends in Ireland.*
-   *Sent by my colleague at the NIH, Brian, while vacationing in California.*
-   *Sent by my childhood friend, Ananya, while exploring the streets of Kyoto, Japan.*
-   *Sent by my cousin Rohan during his summer road trip across Arizona.*

------------------------------------------------------------------------

## **3. Template Variants by Sender Type**

### **A. Colleagues**

Use when the sender is from your workplace (NIH).

> **Template:** “Sent by my colleague at the NIH, \[Name\], while \[context\].”

**Examples:**

-   Sent by my colleague at the NIH, Sucheta, while traveling through Porto, Portugal.
-   Sent by my colleague at the NIH, Jonathan, while hiking in the Swiss Alps.

------------------------------------------------------------------------

### **B. Friends**

When the sender is a personal friend.

> **Template:** “Sent by my friend, \[Name\], while \[context\].”

**Examples:**

-   Sent by my friend, Priya, while spending a weekend in Santorini, Greece.
-   Sent by my friend, Alex, during his photography trip to Banff, Canada.

------------------------------------------------------------------------

### **C. Family Members**

Use this for siblings, cousins, parents, etc.

> **Template:** “Sent by my \[relation\], \[Name\], while \[context\].”

**Examples:**

-   Sent by my cousin, Aarav, while studying abroad in London.
-   Sent by my sister, Neha, during her work trip to Singapore.

------------------------------------------------------------------------

### **D. Self-Sent Postcards**

When you mailed it to yourself while traveling.

> **Template:** “A postcard I sent to myself from \[location\], \[short memory or reason\].”

**Examples:**

-   A postcard I sent to myself from Iceland to remember the surreal landscapes and midnight sun.
-   A postcard I mailed from Yosemite, a reminder of my first solo camping trip.

------------------------------------------------------------------------

### **E. Anonymous / Exchanged Postcards**

For Reddit swaps, Postcrossing, or unexpected finds.

> **Template:** “Sent by \[Name or ‘a fellow traveler’\] from \[location\], as part of \[swap/event/context\].”

**Examples:**

-   Sent by a fellow Redditor stationed at McMurdo Station in Antarctica, as part of a postcard exchange.
-   Sent by Mei from Taiwan through Postcrossing, carrying a beautiful illustration of Tainan’s night markets.

------------------------------------------------------------------------

## **4. Adding Anecdotes & Fun Facts**

Sometimes, the postcard comes with a **story worth telling** — like wrong addresses, unique materials, or special memories. These should **always** go in a **second sentence** after the attribution.

### **Example 1 — Wrong Address (Croatia postcard)**

> Sent by my colleague at the NIH, Brian, while vacationing in Croatia. I had accidentally given him the wrong address — 4550 instead of my actual street number, 5440. Somehow, despite the mix-up, the postcard still reached me on time, as if determined not to lose its way.

### **Example 2 — Unique Material (Porto cork postcard)**

> Sent by my colleague at the NIH, Sucheta, while traveling through Porto, Portugal. This postcard is particularly special because it’s made entirely of cork — the only non-paper postcard in my collection.

### **Example 3 — Historical Note**

> Sent by my friend, Ankit, from Berlin. The postcard features the Brandenburg Gate, once a symbol of division during the Cold War and now an emblem of unity.

------------------------------------------------------------------------

## **5. Formatting Guidelines**

-   Always **italicize place names** for better readability.

    -   Example: “…while vacationing in *California*.”

-   Keep sender names **in full** when possible.

-   Use **en dashes (—)** sparingly, mainly for short, elegant pauses.

-   When a postcard has a **longer story**, break into **two short sentences** for flow.

------------------------------------------------------------------------

## **6. Advanced: Optional Enhancements**

For the **Cards & Stories** book, we can also:

-   **Add sender initials** subtly below captions (e.g., *—BF* for Brian) for a design touch.
-   Include **fun facts or “collection notes”** in sidebars for special postcards.
-   Maintain a **Postcard Index** at the end, sorted by **location** or **sender**.

------------------------------------------------------------------------

## **7. Quick Reference Examples Table**

| **Scenario** | **Harmonized Caption** |
|--------------|----------------------------------------------------------|
| Colleague, simple | Sent by my colleague at the NIH, Vittoria, while visiting friends in *Ireland*. |
| Colleague, unique | Sent by my colleague at the NIH, Sucheta, while traveling through *Porto, Portugal*. This postcard is special because it’s made entirely of cork. |
| Friend | Sent by my friend, Priya, while exploring the beaches of *Bali*. |
| Family | Sent by my cousin, Aarav, during his study exchange in *London*. |
| Self-sent | A postcard I mailed to myself from *Iceland*, a memory of my first Northern Lights experience. |
| Exchange | Sent by a fellow Redditor from *McMurdo Station, Antarctica*, as part of a postcard swap. |
| Anecdote | Sent by my colleague at the NIH, Brian, while vacationing in *Croatia*. Despite giving him the wrong street number, the postcard still found its way to me. |

------------------------------------------------------------------------

## **Next Steps**

If you want, I can create a **ready-to-use Quarto caption template** for your **Cards & Stories** book. This would:

-   Predefine the typography and style for these captions.
-   Allow for **automatic formatting** of sender names, locations, and anecdotes.
-   Make the entire collection visually consistent.

That way, every new postcard caption you add will **automatically follow this polished style**.

------------------------------------------------------------------------

Do you want me to prepare that **Quarto postcard-caption template** next? It’ll integrate this style guide directly into your book layout so you won’t have to format captions manually.