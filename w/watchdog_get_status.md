# Function: <code>watchdog_get_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8168b402)
Location: drivers/watchdog/watchdog_dev.c:165
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff816ebcc0)
Location: drivers/watchdog/watchdog_dev.c:294
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff816ebcc0-ffffffff816ebd10: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8171cbe0)
Location: drivers/watchdog/watchdog_dev.c:295
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff8171cbe0-ffffffff8171cc33: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81734e50)
Location: drivers/watchdog/watchdog_dev.c:303
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff81734e50-ffffffff81734ea3: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817a6ac0)
Location: drivers/watchdog/watchdog_dev.c:304
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff817a6ac0-ffffffff817a6b16: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817ee540)
Location: drivers/watchdog/watchdog_dev.c:324
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff817ee540-ffffffff817ee597: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8181a410)
Location: drivers/watchdog/watchdog_dev.c:324
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff8181a410-ffffffff8181a467: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8185c5f0)
Location: drivers/watchdog/watchdog_dev.c:341
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff8185c5f0-ffffffff8185c647: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8188e1f0)
Location: drivers/watchdog/watchdog_dev.c:340
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff8188e1f0-ffffffff8188e247: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8195cdf0)
Location: drivers/watchdog/watchdog_dev.c:341
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff8195cdf0-ffffffff8195ce4a: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff819637a0)
Location: drivers/watchdog/watchdog_dev.c:342
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff819637a0-ffffffff819637fa: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81947bc0)
Location: drivers/watchdog/watchdog_dev.c:342
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff81947bc0-ffffffff81947c1a: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff819ecb20)
Location: drivers/watchdog/watchdog_dev.c:326
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff819ecb20-ffffffff819ecb7a: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81b53290)
Location: drivers/watchdog/watchdog_dev.c:322
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff81b53290-ffffffff81b532f4: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81cebfb0)
Location: drivers/watchdog/watchdog_dev.c:329
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff81cebfb0-ffffffff81cec014: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81d54c30)
Location: drivers/watchdog/watchdog_dev.c:331
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff81d54c30-ffffffff81d54c94: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0bb00)
Location: drivers/watchdog/watchdog_dev.c:331
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff81e0bb00-ffffffff81e0bb64: watchdog_get_status (STB_LOCAL)
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
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffff800010adf3a0)
Location: drivers/watchdog/watchdog_dev.c:340
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffff800010adf3a0-ffff800010adf464: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (c0bc0afc)
Location: drivers/watchdog/watchdog_dev.c:340
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
c0bc0afc-c0bc0b60: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (c000000000bc6970)
Location: drivers/watchdog/watchdog_dev.c:340
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
c000000000bc6970-c000000000bc6a1c: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d6d7c)
Location: drivers/watchdog/watchdog_dev.c:340
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffe0006d6d7c-ffffffe0006d6dd8: watchdog_get_status (STB_LOCAL)
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
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81834070)
Location: drivers/watchdog/watchdog_dev.c:340
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff81834070-ffffffff818340c7: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817fb700)
Location: drivers/watchdog/watchdog_dev.c:340
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff817fb700-ffffffff817fb757: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff818836a0)
Location: drivers/watchdog/watchdog_dev.c:340
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff818836a0-ffffffff818836f7: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int watchdog_get_status(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8189f160)
Location: drivers/watchdog/watchdog_dev.c:340
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:status_show
```
**Symbols:**

```
ffffffff8189f160-ffffffff8189f1b7: watchdog_get_status (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
