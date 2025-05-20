# Function: <code>__reserve_region_with_split</code>

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
In kernel/resource.c (ffffffff81f7bc6e)
Location: kernel/resource.c:935
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff81fa4a17)
Location: kernel/resource.c:999
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff81fe03dc)
Location: kernel/resource.c:999
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff820c1217)
Location: kernel/resource.c:999
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff826c9408)
Location: kernel/resource.c:1017
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff826f35d8)
Location: kernel/resource.c:986
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff828aa3c0)
Location: kernel/resource.c:981
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff828c2bab)
Location: kernel/resource.c:995
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff828cb1b4)
Location: kernel/resource.c:995
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __reserve_region_with_split(struct resource *root, resource_size_t start, resource_size_t end, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff82ced33c)
Location: kernel/resource.c:995
Inline: False
Direct callers:
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff82ced33c-ffffffff82ced463: __reserve_region_with_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __reserve_region_with_split(struct resource *root, resource_size_t start, resource_size_t end, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff82fd9996)
Location: kernel/resource.c:1002
Inline: False
Direct callers:
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff82fd9996-ffffffff82fd9abd: __reserve_region_with_split (STB_LOCAL)
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
In kernel/resource.c (ffffffff831e4521)
Location: kernel/resource.c:994
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff832c81b3)
Location: kernel/resource.c:994
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff8347b22e)
Location: kernel/resource.c:981
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff83ea5f64)
Location: kernel/resource.c:989
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff836ca634)
Location: kernel/resource.c:989
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff838fb2e4)
Location: kernel/resource.c:1044
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffff80001144281c)
Location: kernel/resource.c:995
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (c151c824)
Location: kernel/resource.c:995
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (c0000000013665a0)
Location: kernel/resource.c:995
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffe000004cec)
Location: kernel/resource.c:995
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff828b3fa7)
Location: kernel/resource.c:995
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff828ac128)
Location: kernel/resource.c:995
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff828c6ea6)
Location: kernel/resource.c:995
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
In kernel/resource.c (ffffffff828cc1f1)
Location: kernel/resource.c:995
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
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
