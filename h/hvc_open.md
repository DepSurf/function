# Function: <code>hvc_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff814fda70)
Location: drivers/tty/hvc/hvc_console.c:338
Inline: False
```
**Symbols:**

```
ffffffff814fda70-ffffffff814fdb7e: hvc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8154e590)
Location: drivers/tty/hvc/hvc_console.c:338
Inline: False
```
**Symbols:**

```
ffffffff8154e590-ffffffff8154e6a2: hvc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8157ae10)
Location: drivers/tty/hvc/hvc_console.c:338
Inline: False
```
**Symbols:**

```
ffffffff8157ae10-ffffffff8157af22: hvc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8158f210)
Location: drivers/tty/hvc/hvc_console.c:337
Inline: False
```
**Symbols:**

```
ffffffff8158f210-ffffffff8158f322: hvc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff815f3df0)
Location: drivers/tty/hvc/hvc_console.c:324
Inline: False
```
**Symbols:**

```
ffffffff815f3df0-ffffffff815f3f08: hvc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8162cda0)
Location: drivers/tty/hvc/hvc_console.c:324
Inline: False
```
**Symbols:**

```
ffffffff8162cda0-ffffffff8162cebe: hvc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8164b100)
Location: drivers/tty/hvc/hvc_console.c:351
Inline: False
```
**Symbols:**

```
ffffffff8164b100-ffffffff8164b21e: hvc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff8167fc40)
Location: drivers/tty/hvc/hvc_console.c:351
Inline: False
```
**Symbols:**

```
ffffffff8167fc40-ffffffff8167fd64: hvc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff816a22f0)
Location: drivers/tty/hvc/hvc_console.c:351
Inline: False
```
**Symbols:**

```
ffffffff816a22f0-ffffffff816a2414: hvc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:347
Inline: False
```
**Symbols:**

```
ffffffff817550e0-ffffffff817551dd: hvc_open (STB_LOCAL)
ffffffff81755622-ffffffff81755635: hvc_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:347
Inline: False
```
**Symbols:**

```
ffffffff81770620-ffffffff8177071d: hvc_open (STB_LOCAL)
ffffffff81c07b15-ffffffff81c07b28: hvc_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:347
Inline: False
```
**Symbols:**

```
ffffffff817540d0-ffffffff817541cd: hvc_open (STB_LOCAL)
ffffffff81bf9774-ffffffff81bf9787: hvc_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:347
Inline: False
```
**Symbols:**

```
ffffffff817d7660-ffffffff817d775d: hvc_open (STB_LOCAL)
ffffffff81cf98d3-ffffffff81cf98e6: hvc_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (0)
Location: drivers/tty/hvc/hvc_console.c:347
Inline: False
```
**Symbols:**

```
ffffffff81915800-ffffffff81915911: hvc_open (STB_LOCAL)
ffffffff81ec1b22-ffffffff81ec1b35: hvc_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81a70b20)
Location: drivers/tty/hvc/hvc_console.c:347
Inline: False
```
**Symbols:**

```
ffffffff81a70b20-ffffffff81a70c3f: hvc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81abb2d0)
Location: drivers/tty/hvc/hvc_console.c:347
Inline: False
```
**Symbols:**

```
ffffffff81abb2d0-ffffffff81abb3ef: hvc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0e030)
Location: drivers/tty/hvc/hvc_console.c:347
Inline: False
```
**Symbols:**

```
ffffffff81b0e030-ffffffff81b0e14f: hvc_open (STB_LOCAL)
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
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffff80001087a6c0)
Location: drivers/tty/hvc/hvc_console.c:351
Inline: False
```
**Symbols:**

```
ffff80001087a6c0-ffff80001087a870: hvc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (c097c654)
Location: drivers/tty/hvc/hvc_console.c:351
Inline: False
```
**Symbols:**

```
c097c654-c097c774: hvc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (c000000000921640)
Location: drivers/tty/hvc/hvc_console.c:351
Inline: False
```
**Symbols:**

```
c000000000921640-c0000000009217e8: hvc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffe00054a45c)
Location: drivers/tty/hvc/hvc_console.c:351
Inline: False
```
**Symbols:**

```
ffffffe00054a45c-ffffffe00054a56c: hvc_open (STB_LOCAL)
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
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81667d50)
Location: drivers/tty/hvc/hvc_console.c:351
Inline: False
```
**Symbols:**

```
ffffffff81667d50-ffffffff81667e74: hvc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff816480d0)
Location: drivers/tty/hvc/hvc_console.c:351
Inline: False
```
**Symbols:**

```
ffffffff816480d0-ffffffff816481f4: hvc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81696130)
Location: drivers/tty/hvc/hvc_console.c:351
Inline: False
```
**Symbols:**

```
ffffffff81696130-ffffffff81696254: hvc_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hvc_open(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff816b06f0)
Location: drivers/tty/hvc/hvc_console.c:351
Inline: False
```
**Symbols:**

```
ffffffff816b06f0-ffffffff816b0814: hvc_open (STB_LOCAL)
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
