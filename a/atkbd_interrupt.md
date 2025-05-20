# Function: <code>atkbd_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff816701c0)
Location: drivers/input/keyboard/atkbd.c:372
Inline: False
```
**Symbols:**

```
ffffffff816701c0-ffffffff816709ac: atkbd_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff816d0510)
Location: drivers/input/keyboard/atkbd.c:372
Inline: False
```
**Symbols:**

```
ffffffff816d0510-ffffffff816d0cab: atkbd_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff816fe3f0)
Location: drivers/input/keyboard/atkbd.c:372
Inline: False
```
**Symbols:**

```
ffffffff816fe3f0-ffffffff816feb8b: atkbd_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff817138e0)
Location: drivers/input/keyboard/atkbd.c:372
Inline: False
```
**Symbols:**

```
ffffffff817138e0-ffffffff81714088: atkbd_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff81784b20)
Location: drivers/input/keyboard/atkbd.c:372
Inline: False
```
**Symbols:**

```
ffffffff81784b20-ffffffff817852cb: atkbd_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff817c5bf0)
Location: drivers/input/keyboard/atkbd.c:372
Inline: False
```
**Symbols:**

```
ffffffff817c5bf0-ffffffff817c6384: atkbd_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff817ed1c0)
Location: drivers/input/keyboard/atkbd.c:372
Inline: False
```
**Symbols:**

```
ffffffff817ed1c0-ffffffff817ed954: atkbd_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:368
Inline: False
```
**Symbols:**

```
ffffffff8182dd40-ffffffff8182e3dd: atkbd_interrupt (STB_LOCAL)
ffffffff8182f2e4-ffffffff8182f3b6: atkbd_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:368
Inline: False
```
**Symbols:**

```
ffffffff8185f670-ffffffff8185fd0d: atkbd_interrupt (STB_LOCAL)
ffffffff81860c14-ffffffff81860ce6: atkbd_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:409
Inline: False
```
**Symbols:**

```
ffffffff81933690-ffffffff81933d73: atkbd_interrupt (STB_LOCAL)
ffffffff81933e72-ffffffff81933f44: atkbd_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:409
Inline: False
```
**Symbols:**

```
ffffffff8193a8e0-ffffffff8193afc3: atkbd_interrupt (STB_LOCAL)
ffffffff81c23655-ffffffff81c23727: atkbd_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:409
Inline: False
```
**Symbols:**

```
ffffffff8191d9e0-ffffffff8191e0c0: atkbd_interrupt (STB_LOCAL)
ffffffff81c156cb-ffffffff81c1579d: atkbd_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:409
Inline: False
```
**Symbols:**

```
ffffffff819c0ec0-ffffffff819c16e9: atkbd_interrupt (STB_LOCAL)
ffffffff81d23e53-ffffffff81d2411b: atkbd_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:397
Inline: False
```
**Symbols:**

```
ffffffff81b1f7d0-ffffffff81b200b5: atkbd_interrupt (STB_LOCAL)
ffffffff81eef9d5-ffffffff81eefc92: atkbd_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:399
Inline: False
```
**Symbols:**

```
ffffffff81cb1a30-ffffffff81cb238c: atkbd_interrupt (STB_LOCAL)
ffffffff820a6e71-ffffffff820a7043: atkbd_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffff800010aa1910)
Location: drivers/input/keyboard/atkbd.c:368
Inline: False
```
**Symbols:**

```
ffff800010aa1910-ffff800010aa2188: atkbd_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (c0b8184c)
Location: drivers/input/keyboard/atkbd.c:368
Inline: False
```
**Symbols:**

```
c0b8184c-c0b82110: atkbd_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (c000000000b82410)
Location: drivers/input/keyboard/atkbd.c:368
Inline: False
```
**Symbols:**

```
c000000000b82410-c000000000b82e80: atkbd_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffe0006af9f0)
Location: drivers/input/keyboard/atkbd.c:368
Inline: False
```
**Symbols:**

```
ffffffe0006af9f0-ffffffe0006b0018: atkbd_interrupt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:368
Inline: False
```
**Symbols:**

```
ffffffff81814680-ffffffff81814d1d: atkbd_interrupt (STB_LOCAL)
ffffffff81815c24-ffffffff81815cf6: atkbd_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:368
Inline: False
```
**Symbols:**

```
ffffffff817dbdb0-ffffffff817dc44d: atkbd_interrupt (STB_LOCAL)
ffffffff817dd324-ffffffff817dd3f6: atkbd_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:368
Inline: False
```
**Symbols:**

```
ffffffff81853800-ffffffff81853e9d: atkbd_interrupt (STB_LOCAL)
ffffffff81854da4-ffffffff81854e76: atkbd_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
irqreturn_t atkbd_interrupt(struct serio *serio, unsigned char data, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:368
Inline: False
```
**Symbols:**

```
ffffffff8186ebd0-ffffffff8186f26d: atkbd_interrupt (STB_LOCAL)
ffffffff8186fece-ffffffff8186ffa0: atkbd_interrupt.cold (STB_LOCAL)
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
