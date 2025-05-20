# Function: <code>__reset_control_put_internal</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __reset_control_put_internal(struct reset_control *rstc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815714e0)
Location: drivers/reset/core.c:325
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_control_release
```
**Symbols:**

```
ffffffff815714e0-ffffffff81571533: __reset_control_put_internal (STB_LOCAL)
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
In drivers/reset/core.c (ffffffff815d5c27)
Location: drivers/reset/core.c:425
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
In drivers/reset/core.c (ffffffff8160ecb7)
Location: drivers/reset/core.c:455
Inline: True
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
In drivers/reset/core.c (ffffffff8162b897)
Location: drivers/reset/core.c:455
Inline: True
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
In drivers/reset/core.c (ffffffff8165f693)
Location: drivers/reset/core.c:594
Inline: True
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
In drivers/reset/core.c (ffffffff81681df3)
Location: drivers/reset/core.c:593
Inline: True
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
In drivers/reset/core.c (ffffffff81732cab)
Location: drivers/reset/core.c:594
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_array_put
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
In drivers/reset/core.c (ffffffff8174ee6b)
Location: drivers/reset/core.c:668
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_array_put
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
In drivers/reset/core.c (ffffffff81732d58)
Location: drivers/reset/core.c:805
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_bulk_put
  - drivers/reset/core.c:__reset_control_bulk_get
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
In drivers/reset/core.c (ffffffff817b3668)
Location: drivers/reset/core.c:805
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_bulk_put
  - drivers/reset/core.c:__reset_control_bulk_get
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
In drivers/reset/core.c (ffffffff818eeef9)
Location: drivers/reset/core.c:806
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_bulk_put
  - drivers/reset/core.c:__reset_control_bulk_get
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
In drivers/reset/core.c (ffffffff81a46b99)
Location: drivers/reset/core.c:806
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_bulk_put
  - drivers/reset/core.c:__reset_control_bulk_get
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
In drivers/reset/core.c (ffffffff81a90d39)
Location: drivers/reset/core.c:806
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_bulk_put
  - drivers/reset/core.c:__reset_control_bulk_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __reset_control_put_internal(struct reset_control *rstc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81ae3820)
Location: drivers/reset/core.c:806
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_control_bulk_release
  - drivers/reset/core.c:__reset_control_bulk_get
```
**Symbols:**

```
ffffffff81ae3820-ffffffff81ae38dc: __reset_control_put_internal (STB_LOCAL)
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
void __reset_control_put_internal(struct reset_control *rstc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffff80001084c8d0)
Location: drivers/reset/core.c:593
Inline: False
Direct callers:
  - drivers/reset/core.c:of_reset_control_array_get
```
**Symbols:**

```
ffff80001084c8d0-ffff80001084c938: __reset_control_put_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __reset_control_put_internal(struct reset_control *rstc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0958bdc)
Location: drivers/reset/core.c:593
Inline: False
Direct callers:
  - drivers/reset/core.c:of_reset_control_array_get
```
**Symbols:**

```
c0958bdc-c0958c38: __reset_control_put_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __reset_control_put_internal(struct reset_control *rstc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0000000008ea9e0)
Location: drivers/reset/core.c:593
Inline: False
Direct callers:
  - drivers/reset/core.c:of_reset_control_array_get
```
**Symbols:**

```
c0000000008ea9e0-c0000000008eaa9c: __reset_control_put_internal (STB_LOCAL)
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
In drivers/reset/core.c (ffffffe00052c57e)
Location: drivers/reset/core.c:593
Inline: True
Inline callers:
  - drivers/reset/core.c:of_reset_control_array_get
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
In drivers/reset/core.c (ffffffff81647873)
Location: drivers/reset/core.c:593
Inline: True
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
In drivers/reset/core.c (ffffffff81627cd3)
Location: drivers/reset/core.c:593
Inline: True
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
In drivers/reset/core.c (ffffffff81675c33)
Location: drivers/reset/core.c:593
Inline: True
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
In drivers/reset/core.c (ffffffff81690293)
Location: drivers/reset/core.c:593
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
