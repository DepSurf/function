# Function: <code>add_badrange</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff816a2727)
Location: drivers/nvdimm/badrange.c:56
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
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
In drivers/nvdimm/badrange.c (ffffffff816de6e7)
Location: drivers/nvdimm/badrange.c:56
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
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
In drivers/nvdimm/badrange.c (ffffffff81700c97)
Location: drivers/nvdimm/badrange.c:56
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
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
In drivers/nvdimm/badrange.c (ffffffff8173ab07)
Location: drivers/nvdimm/badrange.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
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
In drivers/nvdimm/badrange.c (ffffffff8175e7d7)
Location: drivers/nvdimm/badrange.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_badrange(struct badrange *badrange, u64 addr, u64 length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8181e2e0)
Location: drivers/nvdimm/badrange.c:48
Inline: False
Direct callers:
  - drivers/nvdimm/badrange.c:badrange_add
```
**Symbols:**

```
ffffffff8181e2e0-ffffffff8181e3a9: add_badrange (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_badrange(struct badrange *badrange, u64 addr, u64 length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8182d260)
Location: drivers/nvdimm/badrange.c:48
Inline: False
Direct callers:
  - drivers/nvdimm/badrange.c:badrange_add
```
**Symbols:**

```
ffffffff8182d260-ffffffff8182d329: add_badrange (STB_LOCAL)
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
In drivers/nvdimm/badrange.c (ffffffff818103b7)
Location: drivers/nvdimm/badrange.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
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
In drivers/nvdimm/badrange.c (ffffffff8189a9e7)
Location: drivers/nvdimm/badrange.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
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
In drivers/nvdimm/badrange.c (ffffffff819e4127)
Location: drivers/nvdimm/badrange.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
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
In drivers/nvdimm/badrange.c (ffffffff81b5fe27)
Location: drivers/nvdimm/badrange.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
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
In drivers/nvdimm/badrange.c (ffffffff81bb33c7)
Location: drivers/nvdimm/badrange.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
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
In drivers/nvdimm/badrange.c (ffffffff81c078b7)
Location: drivers/nvdimm/badrange.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
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
In drivers/nvdimm/badrange.c (ffff80001095ff18)
Location: drivers/nvdimm/badrange.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (c000000000a12b6c)
Location: drivers/nvdimm/badrange.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
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
In drivers/nvdimm/badrange.c (ffffffe0005cda92)
Location: drivers/nvdimm/badrange.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
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
In drivers/nvdimm/badrange.c (ffffffff81712ec7)
Location: drivers/nvdimm/badrange.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
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
In drivers/nvdimm/badrange.c (ffffffff816e6947)
Location: drivers/nvdimm/badrange.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
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
In drivers/nvdimm/badrange.c (ffffffff81751c97)
Location: drivers/nvdimm/badrange.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
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
In drivers/nvdimm/badrange.c (ffffffff8176ccf7)
Location: drivers/nvdimm/badrange.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_add
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
