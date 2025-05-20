# Function: <code>bind_cdev</code>

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
In drivers/thermal/thermal_core.c (ffffffff81687647)
Location: drivers/thermal/thermal_core.c:317
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e80e2)
Location: drivers/thermal/thermal_core.c:317
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81716a4f)
Location: drivers/thermal/thermal_core.c:854
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8172eda0)
Location: drivers/thermal/thermal_core.c:891
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817a03e0)
Location: drivers/thermal/thermal_core.c:887
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817e79c3)
Location: drivers/thermal/thermal_core.c:884
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81813266)
Location: drivers/thermal/thermal_core.c:888
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff818553a5)
Location: drivers/thermal/thermal_core.c:894
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81886e05)
Location: drivers/thermal/thermal_core.c:894
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void bind_cdev(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:882
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
**Symbols:**

```
ffffffff81955010-ffffffff81955131: bind_cdev (STB_LOCAL)
ffffffff81957329-ffffffff8195733b: bind_cdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void bind_cdev(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:950
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
**Symbols:**

```
ffffffff81959c90-ffffffff81959db1: bind_cdev (STB_LOCAL)
ffffffff81c25aaa-ffffffff81c25abc: bind_cdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void bind_cdev(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:884
Inline: False
```
**Symbols:**

```
ffffffff8193d8b0-ffffffff8193d9d1: bind_cdev (STB_LOCAL)
ffffffff81c17c1e-ffffffff81c17c32: bind_cdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bind_cdev(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:831
Inline: False
```
**Symbols:**

```
ffffffff819e2160-ffffffff819e2281: bind_cdev (STB_LOCAL)
ffffffff81d26d60-ffffffff81d26d74: bind_cdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bind_cdev(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:833
Inline: False
```
**Symbols:**

```
ffffffff81b47890-ffffffff81b479ba: bind_cdev (STB_LOCAL)
ffffffff81ef2be4-ffffffff81ef2bf8: bind_cdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bind_cdev(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81cdef80)
Location: drivers/thermal/thermal_core.c:820
Inline: False
```
**Symbols:**

```
ffffffff81cdef80-ffffffff81cdf0d9: bind_cdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d486f6)
Location: drivers/thermal/thermal_core.c:797
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81dfe9a2)
Location: drivers/thermal/thermal_core.c:864
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad506c)
Location: drivers/thermal/thermal_core.c:894
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb4e1c)
Location: drivers/thermal/thermal_core.c:894
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bbad34)
Location: drivers/thermal/thermal_core.c:894
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffe0006d01b4)
Location: drivers/thermal/thermal_core.c:894
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8182cc85)
Location: drivers/thermal/thermal_core.c:894
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817f4315)
Location: drivers/thermal/thermal_core.c:894
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8187c2b5)
Location: drivers/thermal/thermal_core.c:894
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81897ce5)
Location: drivers/thermal/thermal_core.c:894
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
