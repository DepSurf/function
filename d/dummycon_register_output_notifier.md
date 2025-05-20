# Function: <code>dummycon_register_output_notifier</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
void dummycon_register_output_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffff815b8580)
Location: drivers/video/console/dummycon.c:35
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
```
**Symbols:**

```
ffffffff815b8580-ffffffff815b85d5: dummycon_register_output_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dummycon_register_output_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffff81662400)
Location: drivers/video/console/dummycon.c:35
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_start
```
**Symbols:**

```
ffffffff81662400-ffffffff81662457: dummycon_register_output_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dummycon_register_output_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffff81683090)
Location: drivers/video/console/dummycon.c:35
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_start
```
**Symbols:**

```
ffffffff81683090-ffffffff816830e7: dummycon_register_output_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dummycon_register_output_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffff81665e90)
Location: drivers/video/console/dummycon.c:35
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
```
**Symbols:**

```
ffffffff81665e90-ffffffff81665ee7: dummycon_register_output_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dummycon_register_output_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/console/dummycon.c (0)
Location: drivers/video/console/dummycon.c:35
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
```
**Symbols:**

```
ffffffff81cebf02-ffffffff81cebf16: dummycon_register_output_notifier.cold (STB_LOCAL)
ffffffff816d8ec0-ffffffff816d8f23: dummycon_register_output_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dummycon_register_output_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/console/dummycon.c (0)
Location: drivers/video/console/dummycon.c:35
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
```
**Symbols:**

```
ffffffff81eb3346-ffffffff81eb335b: dummycon_register_output_notifier.cold (STB_LOCAL)
ffffffff81802b80-ffffffff81802bf1: dummycon_register_output_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dummycon_register_output_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/console/dummycon.c (0)
Location: drivers/video/console/dummycon.c:35
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
```
**Symbols:**

```
ffffffff82090358-ffffffff8209036d: dummycon_register_output_notifier.cold (STB_LOCAL)
ffffffff81931270-ffffffff819312e1: dummycon_register_output_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dummycon_register_output_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/console/dummycon.c (0)
Location: drivers/video/console/dummycon.c:35
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
```
**Symbols:**

```
ffffffff821106b8-ffffffff821106cd: dummycon_register_output_notifier.cold (STB_LOCAL)
ffffffff819756c0-ffffffff81975731: dummycon_register_output_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dummycon_register_output_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/console/dummycon.c (0)
Location: drivers/video/console/dummycon.c:36
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
```
**Symbols:**

```
ffffffff821ee4b5-ffffffff821ee4ca: dummycon_register_output_notifier.cold (STB_LOCAL)
ffffffff819bf730-ffffffff819bf7a1: dummycon_register_output_notifier (STB_GLOBAL)
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
void dummycon_register_output_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffff8000107414a0)
Location: drivers/video/console/dummycon.c:35
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
```
**Symbols:**

```
ffff8000107414a0-ffff80001074151c: dummycon_register_output_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dummycon_register_output_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (c08c5fa0)
Location: drivers/video/console/dummycon.c:35
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
```
**Symbols:**

```
c08c5fa0-c08c6034: dummycon_register_output_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dummycon_register_output_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (c00000000089b3d0)
Location: drivers/video/console/dummycon.c:35
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
```
**Symbols:**

```
c00000000089b3d0-c00000000089b488: dummycon_register_output_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dummycon_register_output_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffe0004f0670)
Location: drivers/video/console/dummycon.c:35
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
```
**Symbols:**

```
ffffffe0004f0670-ffffffe0004f06da: dummycon_register_output_notifier (STB_GLOBAL)
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
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dummycon_register_output_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffff815c6710)
Location: drivers/video/console/dummycon.c:35
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fb_console_init
```
**Symbols:**

```
ffffffff815c6710-ffffffff815c6765: dummycon_register_output_notifier (STB_GLOBAL)
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
