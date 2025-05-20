# Function: <code>apply_constraints</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int apply_constraints(struct icc_path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819db8d0)
Location: drivers/interconnect/core.c:275
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
**Symbols:**

```
ffffffff819db8d0-ffffffff819db951: apply_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int apply_constraints(struct icc_path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819daed0)
Location: drivers/interconnect/core.c:283
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
**Symbols:**

```
ffffffff819daed0-ffffffff819daf55: apply_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int apply_constraints(struct icc_path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819c1180)
Location: drivers/interconnect/core.c:283
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
**Symbols:**

```
ffffffff819c1180-ffffffff819c11fa: apply_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int apply_constraints(struct icc_path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:283
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
**Symbols:**

```
ffffffff81a70ed0-ffffffff81a70f6f: apply_constraints (STB_LOCAL)
ffffffff81d3482c-ffffffff81d3484d: apply_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int apply_constraints(struct icc_path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:283
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
**Symbols:**

```
ffffffff81be25a0-ffffffff81be264c: apply_constraints (STB_LOCAL)
ffffffff81f00c82-ffffffff81f00ca3: apply_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int apply_constraints(struct icc_path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:283
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
**Symbols:**

```
ffffffff81d8e090-ffffffff81d8e13c: apply_constraints (STB_LOCAL)
ffffffff820aaa25-ffffffff820aaa46: apply_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int apply_constraints(struct icc_path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:282
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
**Symbols:**

```
ffffffff81dfc970-ffffffff81dfca1c: apply_constraints (STB_LOCAL)
ffffffff8212bf61-ffffffff8212bf82: apply_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int apply_constraints(struct icc_path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:298
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
**Symbols:**

```
ffffffff81eb33c0-ffffffff81eb346c: apply_constraints (STB_LOCAL)
ffffffff8220dc13-ffffffff8220dc34: apply_constraints.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In <code>lowlatency</code>: Absent ⚠️
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
