# Function: <code>wakeup_source_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155b9a0)
Location: drivers/base/power/wakeup.c:191
Inline: False
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff8155b9a0-ffffffff8155ba06: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815adc20)
Location: drivers/base/power/wakeup.c:191
Inline: False
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff815adc20-ffffffff815adc86: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dc9f0)
Location: drivers/base/power/wakeup.c:191
Inline: False
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff815dc9f0-ffffffff815dca56: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f1560)
Location: drivers/base/power/wakeup.c:193
Inline: False
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff815f1560-ffffffff815f15bc: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81658b50)
Location: drivers/base/power/wakeup.c:193
Inline: False
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff81658b50-ffffffff81658bae: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81694680)
Location: drivers/base/power/wakeup.c:197
Inline: False
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff81694680-ffffffff816946dd: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b4d00)
Location: drivers/base/power/wakeup.c:196
Inline: False
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff816b4d00-ffffffff816b4d6e: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (0)
Location: drivers/base/power/wakeup.c:180
Inline: False
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff816efc4c-ffffffff816efc5f: wakeup_source_remove.cold (STB_LOCAL)
ffffffff816eebf0-ffffffff816eec5e: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81712c50)
Location: drivers/base/power/wakeup.c:189
Inline: False
```
**Symbols:**

```
ffffffff81712c50-ffffffff81712cbd: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817ce550)
Location: drivers/base/power/wakeup.c:192
Inline: False
```
**Symbols:**

```
ffffffff817ce550-ffffffff817ce5c0: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e2b90)
Location: drivers/base/power/wakeup.c:192
Inline: False
```
**Symbols:**

```
ffffffff817e2b90-ffffffff817e2c00: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c6f50)
Location: drivers/base/power/wakeup.c:192
Inline: False
```
**Symbols:**

```
ffffffff817c6f50-ffffffff817c6fc0: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81851330)
Location: drivers/base/power/wakeup.c:193
Inline: False
```
**Symbols:**

```
ffffffff81851330-ffffffff818513a0: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81996e90)
Location: drivers/base/power/wakeup.c:193
Inline: False
```
**Symbols:**

```
ffffffff81996e90-ffffffff81996f18: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b07cc0)
Location: drivers/base/power/wakeup.c:193
Inline: False
```
**Symbols:**

```
ffffffff81b07cc0-ffffffff81b07d48: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b55d20)
Location: drivers/base/power/wakeup.c:188
Inline: False
```
**Symbols:**

```
ffffffff81b55d20-ffffffff81b55da8: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81bae2e0)
Location: drivers/base/power/wakeup.c:188
Inline: False
```
**Symbols:**

```
ffffffff81bae2e0-ffffffff81bae368: wakeup_source_remove (STB_GLOBAL)
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
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffff800010904798)
Location: drivers/base/power/wakeup.c:189
Inline: False
```
**Symbols:**

```
ffff800010904798-ffff800010904894: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c09edc14)
Location: drivers/base/power/wakeup.c:189
Inline: False
```
**Symbols:**

```
c09edc14-c09edc9c: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c0000000009a2050)
Location: drivers/base/power/wakeup.c:189
Inline: False
```
**Symbols:**

```
c0000000009a2050-c0000000009a2114: wakeup_source_remove (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d8ff0)
Location: drivers/base/power/wakeup.c:189
Inline: False
```
**Symbols:**

```
ffffffff816d8ff0-ffffffff816d905d: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b3610)
Location: drivers/base/power/wakeup.c:189
Inline: False
```
**Symbols:**

```
ffffffff816b3610-ffffffff816b367d: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81706910)
Location: drivers/base/power/wakeup.c:189
Inline: False
```
**Symbols:**

```
ffffffff81706910-ffffffff8170697d: wakeup_source_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wakeup_source_remove(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81721320)
Location: drivers/base/power/wakeup.c:189
Inline: False
```
**Symbols:**

```
ffffffff81721320-ffffffff8172138d: wakeup_source_remove (STB_GLOBAL)
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
