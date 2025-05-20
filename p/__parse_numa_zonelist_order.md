# Function: <code>__parse_numa_zonelist_order</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __parse_numa_zonelist_order(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811918e0)
Location: mm/page_alloc.c:3910
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_numa_zonelist_order
  - mm/page_alloc.c:numa_zonelist_order_handler
```
**Symbols:**

```
ffffffff811918e0-ffffffff81191938: __parse_numa_zonelist_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __parse_numa_zonelist_order(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a5fe0)
Location: mm/page_alloc.c:4409
Inline: False
Direct callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/page_alloc.c:setup_numa_zonelist_order
```
**Symbols:**

```
ffffffff811a5fe0-ffffffff811a6038: __parse_numa_zonelist_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __parse_numa_zonelist_order(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b6360)
Location: mm/page_alloc.c:4567
Inline: False
Direct callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/page_alloc.c:setup_numa_zonelist_order
```
**Symbols:**

```
ffffffff811b6360-ffffffff811b63b8: __parse_numa_zonelist_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __parse_numa_zonelist_order(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811be230)
Location: mm/page_alloc.c:4854
Inline: False
Direct callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
```
**Symbols:**

```
ffffffff811be230-ffffffff811be288: __parse_numa_zonelist_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __parse_numa_zonelist_order(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d2fd0)
Location: mm/page_alloc.c:4938
Inline: False
Direct callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/page_alloc.c:setup_numa_zonelist_order
```
**Symbols:**

```
ffffffff811d2fd0-ffffffff811d3000: __parse_numa_zonelist_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __parse_numa_zonelist_order(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f4300)
Location: mm/page_alloc.c:5077
Inline: False
Direct callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/page_alloc.c:setup_numa_zonelist_order
```
**Symbols:**

```
ffffffff811f4300-ffffffff811f4330: __parse_numa_zonelist_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __parse_numa_zonelist_order(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812066f0)
Location: mm/page_alloc.c:5243
Inline: False
Direct callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/page_alloc.c:setup_numa_zonelist_order
```
**Symbols:**

```
ffffffff812066f0-ffffffff81206720: __parse_numa_zonelist_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __parse_numa_zonelist_order(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5429
Inline: False
Direct callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/page_alloc.c:setup_numa_zonelist_order
```
**Symbols:**

```
ffffffff8126c6a0-ffffffff8126c6c2: __parse_numa_zonelist_order (STB_LOCAL)
ffffffff812738b8-ffffffff812738d1: __parse_numa_zonelist_order.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __parse_numa_zonelist_order(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5447
Inline: False
Direct callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/page_alloc.c:setup_numa_zonelist_order
```
**Symbols:**

```
ffffffff8127b4b0-ffffffff8127b4d2: __parse_numa_zonelist_order (STB_LOCAL)
ffffffff81282728-ffffffff81282741: __parse_numa_zonelist_order.cold (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff812b3b16)
Location: mm/page_alloc.c:5555
Inline: True
Inline callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
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
In mm/page_alloc.c (ffffffff812bf5e6)
Location: mm/page_alloc.c:5721
Inline: True
Inline callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
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
In mm/page_alloc.c (ffffffff812c4c66)
Location: mm/page_alloc.c:5923
Inline: True
Inline callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
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
In mm/page_alloc.c (ffffffff81308d06)
Location: mm/page_alloc.c:6106
Inline: True
Inline callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
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
In mm/page_alloc.c (ffffffff813711c5)
Location: mm/page_alloc.c:6163
Inline: True
Inline callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
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
In mm/page_alloc.c (ffffffff813ee805)
Location: mm/page_alloc.c:6331
Inline: True
Inline callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
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
In mm/page_alloc.c (ffffffff814199d5)
Location: mm/page_alloc.c:4880
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
In mm/page_alloc.c (ffffffff81446715)
Location: mm/page_alloc.c:4969
Inline: True
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
int __parse_numa_zonelist_order(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010312a18)
Location: mm/page_alloc.c:5447
Inline: False
Direct callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/page_alloc.c:setup_numa_zonelist_order
```
**Symbols:**

```
ffff800010312a18-ffff800010312a74: __parse_numa_zonelist_order (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __parse_numa_zonelist_order(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e3a80)
Location: mm/page_alloc.c:5447
Inline: False
Direct callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/page_alloc.c:setup_numa_zonelist_order
```
**Symbols:**

```
c0000000003e3a80-c0000000003e3ae8: __parse_numa_zonelist_order (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __parse_numa_zonelist_order(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5447
Inline: False
Direct callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/page_alloc.c:setup_numa_zonelist_order
```
**Symbols:**

```
ffffffff81273b00-ffffffff81273b22: __parse_numa_zonelist_order (STB_LOCAL)
ffffffff8127ad78-ffffffff8127ad91: __parse_numa_zonelist_order.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __parse_numa_zonelist_order(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5447
Inline: False
Direct callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/page_alloc.c:setup_numa_zonelist_order
```
**Symbols:**

```
ffffffff81265a70-ffffffff81265a92: __parse_numa_zonelist_order (STB_LOCAL)
ffffffff8126cc58-ffffffff8126cc71: __parse_numa_zonelist_order.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __parse_numa_zonelist_order(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5447
Inline: False
Direct callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/page_alloc.c:setup_numa_zonelist_order
```
**Symbols:**

```
ffffffff812718a0-ffffffff812718c2: __parse_numa_zonelist_order (STB_LOCAL)
ffffffff81278b18-ffffffff81278b31: __parse_numa_zonelist_order.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __parse_numa_zonelist_order(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5447
Inline: False
Direct callers:
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/page_alloc.c:setup_numa_zonelist_order
```
**Symbols:**

```
ffffffff81281300-ffffffff81281322: __parse_numa_zonelist_order (STB_LOCAL)
ffffffff81288708-ffffffff81288721: __parse_numa_zonelist_order.cold (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
