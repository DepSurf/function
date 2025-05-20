# Function: <code>card_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int card_probe(struct pnp_card *card, struct pnp_card_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/card.c (ffffffff814b7710)
Location: drivers/pnp/card.c:70
Inline: False
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff814b7710-ffffffff814b788e: card_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int card_probe(struct pnp_card *card, struct pnp_card_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/card.c (ffffffff81507140)
Location: drivers/pnp/card.c:70
Inline: False
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff81507140-ffffffff815072bd: card_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int card_probe(struct pnp_card *card, struct pnp_card_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/card.c (ffffffff8152b360)
Location: drivers/pnp/card.c:70
Inline: False
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff8152b360-ffffffff8152b4dd: card_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff8153e937)
Location: drivers/pnp/card.c:70
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_add_card
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff8153e440-ffffffff8153e5a8: card_probe.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff815a19c7)
Location: drivers/pnp/card.c:71
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_add_card
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff815a14d0-ffffffff815a163e: card_probe.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff815d964d)
Location: drivers/pnp/card.c:71
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_add_card
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff815d9160-ffffffff815d92c4: card_probe.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff815f2f6d)
Location: drivers/pnp/card.c:71
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_add_card
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff815f2a80-ffffffff815f2be4: card_probe.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff81624e4a)
Location: drivers/pnp/card.c:71
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_add_card
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff81624970-ffffffff81624ad1: card_probe.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff8164693a)
Location: drivers/pnp/card.c:71
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_add_card
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff81646460-ffffffff816465c1: card_probe.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff816f55ea)
Location: drivers/pnp/card.c:71
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_add_card
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff816f51e0-ffffffff816f533e: card_probe.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff8171264a)
Location: drivers/pnp/card.c:71
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_add_card
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff81712240-ffffffff8171239e: card_probe.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff816f3a0a)
Location: drivers/pnp/card.c:71
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_add_card
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff816f3540-ffffffff816f369e: card_probe.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff8176de2a)
Location: drivers/pnp/card.c:71
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_add_card
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff8176d950-ffffffff8176daba: card_probe.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff818a2a90)
Location: drivers/pnp/card.c:71
Inline: True
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff818a2a90-ffffffff818a2c10: card_probe.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff819ec340)
Location: drivers/pnp/card.c:71
Inline: True
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff819ec340-ffffffff819ec4c0: card_probe.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff81a34a60)
Location: drivers/pnp/card.c:71
Inline: True
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff81a34a60-ffffffff81a34c3a: card_probe.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff81a7ff00)
Location: drivers/pnp/card.c:71
Inline: True
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff81a7ff00-ffffffff81a80109: card_probe.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffff8000107b3ab0)
Location: drivers/pnp/card.c:71
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_add_card
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffff8000107b35b8-ffff8000107b3754: card_probe.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff8160c99a)
Location: drivers/pnp/card.c:71
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_add_card
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff8160c4c0-ffffffff8160c621: card_probe.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff81600eea)
Location: drivers/pnp/card.c:71
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_add_card
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff81600a10-ffffffff81600b71: card_probe.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff8163a77a)
Location: drivers/pnp/card.c:71
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_add_card
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff8163a2a0-ffffffff8163a401: card_probe.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pnp/card.c (ffffffff81654aca)
Location: drivers/pnp/card.c:71
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_add_card
Direct callers:
  - drivers/pnp/card.c:pnp_add_card
```
**Symbols:**

```
ffffffff816545f0-ffffffff81654751: card_probe.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
