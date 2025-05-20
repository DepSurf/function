# Function: <code>wakeup_source_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155b8d0)
Location: drivers/base/power/wakeup.c:169
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff8155b8d0-ffffffff8155b96b: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815adb50)
Location: drivers/base/power/wakeup.c:169
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff815adb50-ffffffff815adbeb: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dc920)
Location: drivers/base/power/wakeup.c:169
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff815dc920-ffffffff815dc9bb: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f14a0)
Location: drivers/base/power/wakeup.c:171
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff815f14a0-ffffffff815f1527: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81658a90)
Location: drivers/base/power/wakeup.c:171
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff81658a90-ffffffff81658b15: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81694600)
Location: drivers/base/power/wakeup.c:176
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff81694600-ffffffff8169467b: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b4c80)
Location: drivers/base/power/wakeup.c:175
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff816b4c80-ffffffff816b4cfb: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (0)
Location: drivers/base/power/wakeup.c:159
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff816efc39-ffffffff816efc4c: wakeup_source_add.cold (STB_LOCAL)
ffffffff816eeb40-ffffffff816eebbb: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81712bd0)
Location: drivers/base/power/wakeup.c:168
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff81712bd0-ffffffff81712c4a: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817ce4d0)
Location: drivers/base/power/wakeup.c:171
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff817ce4d0-ffffffff817ce54d: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e2b10)
Location: drivers/base/power/wakeup.c:171
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff817e2b10-ffffffff817e2b8d: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c6ed0)
Location: drivers/base/power/wakeup.c:171
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff817c6ed0-ffffffff817c6f4d: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff818512b0)
Location: drivers/base/power/wakeup.c:172
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff818512b0-ffffffff8185132d: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81996de0)
Location: drivers/base/power/wakeup.c:172
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff81996de0-ffffffff81996e83: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b07c00)
Location: drivers/base/power/wakeup.c:172
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff81b07c00-ffffffff81b07ca3: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b55c60)
Location: drivers/base/power/wakeup.c:167
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff81b55c60-ffffffff81b55d03: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81bae220)
Location: drivers/base/power/wakeup.c:167
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff81bae220-ffffffff81bae2c3: wakeup_source_add (STB_GLOBAL)
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
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffff8000109049d8)
Location: drivers/base/power/wakeup.c:168
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffff8000109049d8-ffff800010904af0: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c09edb58)
Location: drivers/base/power/wakeup.c:168
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
c09edb58-c09edc14: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c0000000009a1f70)
Location: drivers/base/power/wakeup.c:168
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
c0000000009a1f70-c0000000009a2044: wakeup_source_add (STB_GLOBAL)
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
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d8f70)
Location: drivers/base/power/wakeup.c:168
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff816d8f70-ffffffff816d8fea: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b3590)
Location: drivers/base/power/wakeup.c:168
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff816b3590-ffffffff816b360a: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81706890)
Location: drivers/base/power/wakeup.c:168
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff81706890-ffffffff8170690a: wakeup_source_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wakeup_source_add(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817212a0)
Location: drivers/base/power/wakeup.c:168
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff817212a0-ffffffff8172131a: wakeup_source_add (STB_GLOBAL)
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
