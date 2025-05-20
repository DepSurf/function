# Function: <code>__watchdog_register_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff8168ab60)
Location: drivers/watchdog/watchdog_core.c:140
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff8168ab60-ffffffff8168ad19: __watchdog_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff816eb930)
Location: drivers/watchdog/watchdog_core.c:194
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff816eb930-ffffffff816ebb14: __watchdog_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff8171c850)
Location: drivers/watchdog/watchdog_core.c:194
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff8171c850-ffffffff8171ca34: __watchdog_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff81734ae0)
Location: drivers/watchdog/watchdog_core.c:194
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff81734ae0-ffffffff81734cac: __watchdog_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff817a67b0)
Location: drivers/watchdog/watchdog_core.c:175
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff817a67b0-ffffffff817a691a: __watchdog_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:176
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff817ee220-ffffffff817ee35f: __watchdog_register_device (STB_LOCAL)
ffffffff817ee4d2-ffffffff817ee503: __watchdog_register_device.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:176
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff8181a0f0-ffffffff8181a22f: __watchdog_register_device (STB_LOCAL)
ffffffff8181a3a2-ffffffff8181a3d3: __watchdog_register_device.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:185
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff8185c260-ffffffff8185c38a: __watchdog_register_device (STB_LOCAL)
ffffffff8185c530-ffffffff8185c561: __watchdog_register_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:204
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff8188dde0-ffffffff8188df4b: __watchdog_register_device (STB_LOCAL)
ffffffff8188e0f0-ffffffff8188e155: __watchdog_register_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:208
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff8195c990-ffffffff8195cb41: __watchdog_register_device (STB_LOCAL)
ffffffff8195ccf0-ffffffff8195cd55: __watchdog_register_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:208
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff81963450-ffffffff819635fa: __watchdog_register_device (STB_LOCAL)
ffffffff81c25dd4-ffffffff81c25e4e: __watchdog_register_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:208
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff81947870-ffffffff81947a1b: __watchdog_register_device (STB_LOCAL)
ffffffff81c17f54-ffffffff81c17fd3: __watchdog_register_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:236
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff819ec770-ffffffff819ec95c: __watchdog_register_device (STB_LOCAL)
ffffffff81d272fb-ffffffff81d27391: __watchdog_register_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:236
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff81b52eb0-ffffffff81b53096: __watchdog_register_device (STB_LOCAL)
ffffffff81ef31a6-ffffffff81ef322d: __watchdog_register_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff81ceb860)
Location: drivers/watchdog/watchdog_core.c:240
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff81ceb860-ffffffff81cebabc: __watchdog_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff81d544b0)
Location: drivers/watchdog/watchdog_core.c:240
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff81d544b0-ffffffff81d5470c: __watchdog_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff81e0b380)
Location: drivers/watchdog/watchdog_core.c:240
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff81e0b380-ffffffff81e0b5dc: __watchdog_register_device (STB_LOCAL)
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
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffff800010ade7d0)
Location: drivers/watchdog/watchdog_core.c:204
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffff800010ade7d0-ffff800010adea44: __watchdog_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (c0bc0340)
Location: drivers/watchdog/watchdog_core.c:204
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
c0bc0340-c0bc054c: __watchdog_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (c000000000bc6190)
Location: drivers/watchdog/watchdog_core.c:204
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
c000000000bc6190-c000000000bc64c0: __watchdog_register_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffe0006d692c)
Location: drivers/watchdog/watchdog_core.c:204
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffe0006d692c-ffffffe0006d6afa: __watchdog_register_device (STB_LOCAL)
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
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:204
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff81833c60-ffffffff81833dcb: __watchdog_register_device (STB_LOCAL)
ffffffff81833f70-ffffffff81833fd5: __watchdog_register_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:204
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff817fb2f0-ffffffff817fb45b: __watchdog_register_device (STB_LOCAL)
ffffffff817fb600-ffffffff817fb665: __watchdog_register_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:204
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff81883290-ffffffff818833fb: __watchdog_register_device (STB_LOCAL)
ffffffff818835a0-ffffffff81883605: __watchdog_register_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __watchdog_register_device(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_core.c (0)
Location: drivers/watchdog/watchdog_core.c:204
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_core.c:watchdog_init
  - drivers/watchdog/watchdog_core.c:watchdog_register_device
```
**Symbols:**

```
ffffffff8189ed50-ffffffff8189eebb: __watchdog_register_device (STB_LOCAL)
ffffffff8189f060-ffffffff8189f0c5: __watchdog_register_device.cold (STB_LOCAL)
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
