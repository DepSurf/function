# Function: <code>wm831x_set_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81582540)
Location: drivers/mfd/wm831x-core.c:599
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff81582540-ffffffff815825af: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff815d8610)
Location: drivers/mfd/wm831x-core.c:599
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff815d8610-ffffffff815d8694: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81605300)
Location: drivers/mfd/wm831x-core.c:599
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff81605300-ffffffff81605384: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81619220)
Location: drivers/mfd/wm831x-core.c:601
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff81619220-ffffffff8161929a: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff816818d0)
Location: drivers/mfd/wm831x-core.c:601
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff816818d0-ffffffff8168194a: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff816bd940)
Location: drivers/mfd/wm831x-core.c:601
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff816bd940-ffffffff816bd9ba: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff816dec80)
Location: drivers/mfd/wm831x-core.c:601
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff816dec80-ffffffff816decfa: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81718430)
Location: drivers/mfd/wm831x-core.c:597
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff81718430-ffffffff817184ab: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff8173c740)
Location: drivers/mfd/wm831x-core.c:597
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff8173c740-ffffffff8173c7bb: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff817fa0a0)
Location: drivers/mfd/wm831x-core.c:597
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff817fa0a0-ffffffff817fa135: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff8180ca20)
Location: drivers/mfd/wm831x-core.c:601
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff8180ca20-ffffffff8180cab5: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff817f1330)
Location: drivers/mfd/wm831x-core.c:601
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff817f1330-ffffffff817f13c1: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff818799c0)
Location: drivers/mfd/wm831x-core.c:601
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff818799c0-ffffffff81879a51: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff819c20e0)
Location: drivers/mfd/wm831x-core.c:601
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff819c20e0-ffffffff819c2180: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81b37b70)
Location: drivers/mfd/wm831x-core.c:601
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff81b37b70-ffffffff81b37c10: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81b8afd0)
Location: drivers/mfd/wm831x-core.c:601
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff81b8afd0-ffffffff81b8b07d: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81bdeed0)
Location: drivers/mfd/wm831x-core.c:600
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff81bdeed0-ffffffff81bdef7d: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffff8000109378a8)
Location: drivers/mfd/wm831x-core.c:597
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffff8000109378a8-ffff800010937934: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (c0a1fd24)
Location: drivers/mfd/wm831x-core.c:597
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
c0a1fd24-c0a1fdb0: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (c0000000009de070)
Location: drivers/mfd/wm831x-core.c:597
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
c0000000009de070-c0000000009de138: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffe0005ac814)
Location: drivers/mfd/wm831x-core.c:597
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffe0005ac814-ffffffe0005ac88c: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81700220)
Location: drivers/mfd/wm831x-core.c:597
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff81700220-ffffffff8170029b: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff816d4030)
Location: drivers/mfd/wm831x-core.c:597
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff816d4030-ffffffff816d40ab: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff8172fc00)
Location: drivers/mfd/wm831x-core.c:597
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff8172fc00-ffffffff8172fc7b: wm831x_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int wm831x_set_bits(struct wm831x *wm831x, short unsigned int reg, short unsigned int mask, short unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff8174b040)
Location: drivers/mfd/wm831x-core.c:597
Inline: False
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_sync_unlock
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
**Symbols:**

```
ffffffff8174b040-ffffffff8174b0bb: wm831x_set_bits (STB_GLOBAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
