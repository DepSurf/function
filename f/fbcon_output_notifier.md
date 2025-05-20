# Function: <code>fbcon_output_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fbcon_output_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c9b2c)
Location: drivers/video/fbdev/core/fbcon.c:3582
Inline: True
```
**Symbols:**

```
ffffffff815c5290-ffffffff815c52bf: fbcon_output_notifier (STB_LOCAL)
ffffffff815c9b2c-ffffffff815c9b74: fbcon_output_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fbcon_output_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8166f903)
Location: drivers/video/fbdev/core/fbcon.c:3290
Inline: True
```
**Symbols:**

```
ffffffff8166f8f0-ffffffff8166f95a: fbcon_output_notifier (STB_LOCAL)
ffffffff816734b7-ffffffff816734be: fbcon_output_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fbcon_output_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8168fe13)
Location: drivers/video/fbdev/core/fbcon.c:3240
Inline: True
```
**Symbols:**

```
ffffffff8168fe00-ffffffff8168fe6a: fbcon_output_notifier (STB_LOCAL)
ffffffff81bff13b-ffffffff81bff142: fbcon_output_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fbcon_output_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81672b23)
Location: drivers/video/fbdev/core/fbcon.c:3232
Inline: True
```
**Symbols:**

```
ffffffff81672b10-ffffffff81672b7a: fbcon_output_notifier (STB_LOCAL)
ffffffff81bf0bad-ffffffff81bf0bb4: fbcon_output_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fbcon_output_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff816e6b43)
Location: drivers/video/fbdev/core/fbcon.c:3277
Inline: True
```
**Symbols:**

```
ffffffff816e6b30-ffffffff816e6b9a: fbcon_output_notifier (STB_LOCAL)
ffffffff81cec717-ffffffff81cec71e: fbcon_output_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fbcon_output_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81eb3b38)
Location: drivers/video/fbdev/core/fbcon.c:3353
Inline: True
```
**Symbols:**

```
ffffffff81810970-ffffffff8181099f: fbcon_output_notifier (STB_LOCAL)
ffffffff81eb3b38-ffffffff81eb3b79: fbcon_output_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fbcon_output_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8193f360)
Location: drivers/video/fbdev/core/fbcon.c:3351
Inline: False
```
**Symbols:**

```
ffffffff8193f360-ffffffff8193f3c5: fbcon_output_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fbcon_output_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81983870)
Location: drivers/video/fbdev/core/fbcon.c:3344
Inline: False
```
**Symbols:**

```
ffffffff81983870-ffffffff819838d5: fbcon_output_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fbcon_output_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819cd8f0)
Location: drivers/video/fbdev/core/fbcon.c:3344
Inline: False
```
**Symbols:**

```
ffffffff819cd8f0-ffffffff819cd955: fbcon_output_notifier (STB_LOCAL)
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
int fbcon_output_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffff80001074e848)
Location: drivers/video/fbdev/core/fbcon.c:3582
Inline: True
```
**Symbols:**

```
ffff80001074e848-ffff80001074e8d0: fbcon_output_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fbcon_output_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c08d13d4)
Location: drivers/video/fbdev/core/fbcon.c:3582
Inline: True
```
**Symbols:**

```
c08d13d4-c08d147c: fbcon_output_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fbcon_output_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c0000000008b28f0)
Location: drivers/video/fbdev/core/fbcon.c:3582
Inline: True
```
**Symbols:**

```
c0000000008b28f0-c0000000008b29b8: fbcon_output_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fbcon_output_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004fcc9c)
Location: drivers/video/fbdev/core/fbcon.c:3582
Inline: True
```
**Symbols:**

```
ffffffe0004fcc9c-ffffffe0004fcd28: fbcon_output_notifier (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fbcon_output_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d7c6c)
Location: drivers/video/fbdev/core/fbcon.c:3582
Inline: True
```
**Symbols:**

```
ffffffff815d33d0-ffffffff815d33ff: fbcon_output_notifier (STB_LOCAL)
ffffffff815d7c6c-ffffffff815d7cb4: fbcon_output_notifier.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
