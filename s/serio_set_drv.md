# Function: <code>serio_set_drv</code>

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
In drivers/input/serio/serio.c (ffffffff81663f2d)
Location: drivers/input/serio/serio.c:893
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
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
In drivers/input/serio/serio.c (ffffffff816c412d)
Location: drivers/input/serio/serio.c:893
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
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
In drivers/input/serio/serio.c (ffffffff816f20ed)
Location: drivers/input/serio/serio.c:893
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
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
In drivers/input/serio/serio.c (ffffffff817079dd)
Location: drivers/input/serio/serio.c:893
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
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
In drivers/input/serio/serio.c (ffffffff81778bc0)
Location: drivers/input/serio/serio.c:893
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
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
In drivers/input/serio/serio.c (ffffffff817b9880)
Location: drivers/input/serio/serio.c:893
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
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
In drivers/input/serio/serio.c (ffffffff817e0c90)
Location: drivers/input/serio/serio.c:889
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
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
In drivers/input/serio/serio.c (ffffffff81821570)
Location: drivers/input/serio/serio.c:877
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
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
In drivers/input/serio/serio.c (ffffffff818529e0)
Location: drivers/input/serio/serio.c:877
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void serio_set_drv(struct serio *serio, struct serio_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81924b10)
Location: drivers/input/serio/serio.c:877
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
Direct callers:
  - drivers/input/serio/serio.c:serio_open
```
**Symbols:**

```
ffffffff81924aa0-ffffffff81924ae2: serio_set_drv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void serio_set_drv(struct serio *serio, struct serio_driver *drv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff8192c8c0)
Location: drivers/input/serio/serio.c:877
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
Direct callers:
  - drivers/input/serio/serio.c:serio_open
```
**Symbols:**

```
ffffffff8192c850-ffffffff8192c892: serio_set_drv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff8190fca0)
Location: drivers/input/serio/serio.c:877
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff819b0b90)
Location: drivers/input/serio/serio.c:876
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81b0e980)
Location: drivers/input/serio/serio.c:876
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81c9ec00)
Location: drivers/input/serio/serio.c:873
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
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
In drivers/input/serio/serio.c (ffffffff81d05f40)
Location: drivers/input/serio/serio.c:873
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
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
In drivers/input/serio/serio.c (ffffffff81dbbb40)
Location: drivers/input/serio/serio.c:873
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
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
In drivers/input/serio/serio.c (ffff800010a92448)
Location: drivers/input/serio/serio.c:877
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void serio_set_drv(struct serio *serio, struct serio_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (c0b75398)
Location: drivers/input/serio/serio.c:877
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
```
**Symbols:**

```
c0b75398-c0b753e0: serio_set_drv (STB_LOCAL)
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
In drivers/input/serio/serio.c (c000000000b6ee60)
Location: drivers/input/serio/serio.c:877
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
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
In drivers/input/serio/serio.c (ffffffe0006a5230)
Location: drivers/input/serio/serio.c:877
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
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
In drivers/input/serio/serio.c (ffffffff81807ac0)
Location: drivers/input/serio/serio.c:877
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
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
In drivers/input/serio/serio.c (ffffffff817cf1d0)
Location: drivers/input/serio/serio.c:877
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
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
In drivers/input/serio/serio.c (ffffffff81846b70)
Location: drivers/input/serio/serio.c:877
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
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
In drivers/input/serio/serio.c (ffffffff81861290)
Location: drivers/input/serio/serio.c:877
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_close
  - drivers/input/serio/serio.c:serio_open
  - drivers/input/serio/serio.c:serio_open
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
</ul>
<b>Arch</b>
<ul>
</ul>
