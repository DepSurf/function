# Function: <code>hvc_close</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff814fdeb0)
Location: drivers/tty/hvc/hvc_console.c:381
Inline: True
```
**Symbols:**

```
ffffffff814fdeb0-ffffffff814fdfa6: hvc_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8154e9e0)
Location: drivers/tty/hvc/hvc_console.c:381
Inline: True
```
**Symbols:**

```
ffffffff8154e9e0-ffffffff8154ead6: hvc_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8157b260)
Location: drivers/tty/hvc/hvc_console.c:381
Inline: True
```
**Symbols:**

```
ffffffff8157b260-ffffffff8157b356: hvc_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8158f510)
Location: drivers/tty/hvc/hvc_console.c:380
Inline: True
```
**Symbols:**

```
ffffffff8158f510-ffffffff8158f606: hvc_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff815f4010)
Location: drivers/tty/hvc/hvc_console.c:367
Inline: True
```
**Symbols:**

```
ffffffff815f4010-ffffffff815f410c: hvc_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:367
Inline: True
```
**Symbols:**

```
ffffffff8162cf50-ffffffff8162d035: hvc_close (STB_LOCAL)
ffffffff8162da09-ffffffff8162da20: hvc_close.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8164b33f)
Location: drivers/tty/hvc/hvc_console.c:394
Inline: True
```
**Symbols:**

```
ffffffff8164b320-ffffffff8164b405: hvc_close (STB_LOCAL)
ffffffff8164bc89-ffffffff8164bca0: hvc_close.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8167fe8f)
Location: drivers/tty/hvc/hvc_console.c:394
Inline: True
```
**Symbols:**

```
ffffffff8167fe70-ffffffff8167ff55: hvc_close (STB_LOCAL)
ffffffff816807a9-ffffffff816807c0: hvc_close.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff816a253f)
Location: drivers/tty/hvc/hvc_console.c:394
Inline: True
```
**Symbols:**

```
ffffffff816a2520-ffffffff816a2605: hvc_close (STB_LOCAL)
ffffffff816a2e59-ffffffff816a2e70: hvc_close.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:389
Inline: False
```
**Symbols:**

```
ffffffff81754670-ffffffff8175476c: hvc_close (STB_LOCAL)
ffffffff817555bf-ffffffff817555d6: hvc_close.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:389
Inline: False
```
**Symbols:**

```
ffffffff8176f8e0-ffffffff8176f9dc: hvc_close (STB_LOCAL)
ffffffff81c07ab2-ffffffff81c07ac9: hvc_close.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:389
Inline: False
```
**Symbols:**

```
ffffffff817533c0-ffffffff817534bc: hvc_close (STB_LOCAL)
ffffffff81bf96ec-ffffffff81bf9703: hvc_close.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:389
Inline: False
```
**Symbols:**

```
ffffffff817d67b0-ffffffff817d68ac: hvc_close (STB_LOCAL)
ffffffff81cf9865-ffffffff81cf987c: hvc_close.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:389
Inline: False
```
**Symbols:**

```
ffffffff81914850-ffffffff8191497e: hvc_close (STB_LOCAL)
ffffffff81ec1aa9-ffffffff81ec1ac2: hvc_close.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81a6f920)
Location: drivers/tty/hvc/hvc_console.c:389
Inline: False
```
**Symbols:**

```
ffffffff81a6f920-ffffffff81a6fa67: hvc_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81aba0d0)
Location: drivers/tty/hvc/hvc_console.c:389
Inline: False
```
**Symbols:**

```
ffffffff81aba0d0-ffffffff81aba217: hvc_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0ce00)
Location: drivers/tty/hvc/hvc_console.c:389
Inline: False
```
**Symbols:**

```
ffffffff81b0ce00-ffffffff81b0cf47: hvc_close (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffff80001087a870)
Location: drivers/tty/hvc/hvc_console.c:394
Inline: True
```
**Symbols:**

```
ffff80001087a870-ffff80001087a9d0: hvc_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (c097c870)
Location: drivers/tty/hvc/hvc_console.c:394
Inline: True
```
**Symbols:**

```
c097c870-c097c968: hvc_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (c0000000009219a0)
Location: drivers/tty/hvc/hvc_console.c:394
Inline: True
```
**Symbols:**

```
c0000000009219a0-c000000000921b3c: hvc_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffe00054a7ca)
Location: drivers/tty/hvc/hvc_console.c:394
Inline: True
```
**Symbols:**

```
ffffffe00054a7ca-ffffffe00054a8b6: hvc_close (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81667f9f)
Location: drivers/tty/hvc/hvc_console.c:394
Inline: True
```
**Symbols:**

```
ffffffff81667f80-ffffffff81668065: hvc_close (STB_LOCAL)
ffffffff816688b9-ffffffff816688d0: hvc_close.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8164831f)
Location: drivers/tty/hvc/hvc_console.c:394
Inline: True
```
**Symbols:**

```
ffffffff81648300-ffffffff816483e5: hvc_close (STB_LOCAL)
ffffffff81648c39-ffffffff81648c50: hvc_close.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8169637f)
Location: drivers/tty/hvc/hvc_console.c:394
Inline: True
```
**Symbols:**

```
ffffffff81696360-ffffffff81696445: hvc_close (STB_LOCAL)
ffffffff81696c99-ffffffff81696cb0: hvc_close.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hvc_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff816b093f)
Location: drivers/tty/hvc/hvc_console.c:394
Inline: True
```
**Symbols:**

```
ffffffff816b0920-ffffffff816b0a05: hvc_close (STB_LOCAL)
ffffffff816b1249-ffffffff816b1260: hvc_close.cold (STB_LOCAL)
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
