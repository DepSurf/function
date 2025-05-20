# Function: <code>loop_config_discard</code>

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
In drivers/block/loop.c (ffffffff8156e2d2)
Location: drivers/block/loop.c:859
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
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
In drivers/block/loop.c (ffffffff815c3bd0)
Location: drivers/block/loop.c:854
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
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
In drivers/block/loop.c (ffffffff815f230e)
Location: drivers/block/loop.c:830
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
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
In drivers/block/loop.c (ffffffff816064fc)
Location: drivers/block/loop.c:853
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
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
In drivers/block/loop.c (ffffffff8166e91f)
Location: drivers/block/loop.c:842
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
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
In drivers/block/loop.c (ffffffff816aa3e7)
Location: drivers/block/loop.c:893
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
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
In drivers/block/loop.c (ffffffff816cb034)
Location: drivers/block/loop.c:890
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
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
In drivers/block/loop.c (ffffffff8170661a)
Location: drivers/block/loop.c:890
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
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
In drivers/block/loop.c (ffffffff8172a86a)
Location: drivers/block/loop.c:900
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817ea17a)
Location: drivers/block/loop.c:915
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817febda)
Location: drivers/block/loop.c:913
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void loop_config_discard(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e0370)
Location: drivers/block/loop.c:926
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff817e0370-ffffffff817e0478: loop_config_discard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void loop_config_discard(struct loop_device *lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8186c260)
Location: drivers/block/loop.c:952
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff8186c260-ffffffff8186c3a8: loop_config_discard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff819b5cb0)
Location: drivers/block/loop.c:757
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff819b5cb0-ffffffff819b5dd7: loop_config_discard.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff81b2ade0)
Location: drivers/block/loop.c:757
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff81b2ade0-ffffffff81b2af07: loop_config_discard.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff81b7b0d0)
Location: drivers/block/loop.c:757
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff81b7b0d0-ffffffff81b7b1f7: loop_config_discard.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff81bceec0)
Location: drivers/block/loop.c:753
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff81bceec0-ffffffff81bcefe7: loop_config_discard.isra.0 (STB_LOCAL)
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
In drivers/block/loop.c (ffff80001092146c)
Location: drivers/block/loop.c:900
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
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
In drivers/block/loop.c (c0a06adc)
Location: drivers/block/loop.c:900
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
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
In drivers/block/loop.c (c0000000009c57c0)
Location: drivers/block/loop.c:900
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
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
In drivers/block/loop.c (ffffffe0005a0124)
Location: drivers/block/loop.c:900
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
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
In drivers/block/loop.c (ffffffff816f064a)
Location: drivers/block/loop.c:900
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
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
In drivers/block/loop.c (ffffffff816ca75a)
Location: drivers/block/loop.c:900
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
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
In drivers/block/loop.c (ffffffff8171dd2a)
Location: drivers/block/loop.c:900
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
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
In drivers/block/loop.c (ffffffff817390ba)
Location: drivers/block/loop.c:900
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_set_status
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
