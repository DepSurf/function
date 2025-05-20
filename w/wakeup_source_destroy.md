# Function: <code>wakeup_source_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155c140)
Location: drivers/base/power/wakeup.c:153
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff8155c140-ffffffff8155c21d: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815ae340)
Location: drivers/base/power/wakeup.c:153
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff815ae340-ffffffff815ae418: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dd140)
Location: drivers/base/power/wakeup.c:153
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff815dd140-ffffffff815dd217: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f20a0)
Location: drivers/base/power/wakeup.c:155
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff815f1f20-ffffffff815f1fe7: wakeup_source_destroy.part.7 (STB_LOCAL)
ffffffff815f1ff0-ffffffff815f2007: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81659650)
Location: drivers/base/power/wakeup.c:155
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff816594d0-ffffffff81659594: wakeup_source_destroy.part.8 (STB_LOCAL)
ffffffff816595a0-ffffffff816595b7: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81695280)
Location: drivers/base/power/wakeup.c:160
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff81694ce0-ffffffff81694da4: wakeup_source_destroy.part.12 (STB_LOCAL)
ffffffff81694db0-ffffffff81694dc6: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b58f0)
Location: drivers/base/power/wakeup.c:159
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff816b5390-ffffffff816b5448: wakeup_source_destroy.part.12 (STB_LOCAL)
ffffffff816b5450-ffffffff816b5466: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816ef711)
Location: drivers/base/power/wakeup.c:143
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff816eef20-ffffffff816eefe4: wakeup_source_destroy.part.0 (STB_LOCAL)
ffffffff816eeff0-ffffffff816ef006: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81713140)
Location: drivers/base/power/wakeup.c:153
Inline: True
```
**Symbols:**

```
ffffffff81713140-ffffffff8171316d: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817cedc6)
Location: drivers/base/power/wakeup.c:156
Inline: True
```
**Symbols:**

```
ffffffff817cee70-ffffffff817ceeb9: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e33c6)
Location: drivers/base/power/wakeup.c:156
Inline: True
```
**Symbols:**

```
ffffffff817e3470-ffffffff817e34b9: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c7786)
Location: drivers/base/power/wakeup.c:156
Inline: True
```
**Symbols:**

```
ffffffff817c7830-ffffffff817c7879: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81851b26)
Location: drivers/base/power/wakeup.c:157
Inline: True
```
**Symbols:**

```
ffffffff81851bd0-ffffffff81851c19: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff819979b4)
Location: drivers/base/power/wakeup.c:157
Inline: True
```
**Symbols:**

```
ffffffff81997b10-ffffffff81997b65: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b08974)
Location: drivers/base/power/wakeup.c:157
Inline: True
```
**Symbols:**

```
ffffffff81b08b10-ffffffff81b08b65: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b56994)
Location: drivers/base/power/wakeup.c:152
Inline: True
```
**Symbols:**

```
ffffffff81b56b30-ffffffff81b56b85: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81baef84)
Location: drivers/base/power/wakeup.c:152
Inline: True
```
**Symbols:**

```
ffffffff81baf120-ffffffff81baf175: wakeup_source_destroy (STB_GLOBAL)
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
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffff8000109041f0)
Location: drivers/base/power/wakeup.c:153
Inline: True
```
**Symbols:**

```
ffff8000109041f0-ffff800010904230: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c09ee25c)
Location: drivers/base/power/wakeup.c:153
Inline: True
```
**Symbols:**

```
c09ee25c-c09ee290: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c0000000009a2800)
Location: drivers/base/power/wakeup.c:153
Inline: True
```
**Symbols:**

```
c0000000009a2800-c0000000009a285c: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d94c0)
Location: drivers/base/power/wakeup.c:153
Inline: True
```
**Symbols:**

```
ffffffff816d94c0-ffffffff816d94ed: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b3b00)
Location: drivers/base/power/wakeup.c:153
Inline: True
```
**Symbols:**

```
ffffffff816b3b00-ffffffff816b3b2d: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81706e00)
Location: drivers/base/power/wakeup.c:153
Inline: True
```
**Symbols:**

```
ffffffff81706e00-ffffffff81706e2d: wakeup_source_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_destroy(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81721830)
Location: drivers/base/power/wakeup.c:153
Inline: True
```
**Symbols:**

```
ffffffff81721830-ffffffff8172185d: wakeup_source_destroy (STB_GLOBAL)
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
