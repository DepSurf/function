# Function: <code>__xdp_reg_mem_model</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct xdp_mem_allocator *__xdp_reg_mem_model(struct xdp_mem_info *mem, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/xdp.c (0)
Location: net/core/xdp.c:270
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_reg_mem_model
```
**Symbols:**

```
ffffffff81c508f0-ffffffff81c50bbe: __xdp_reg_mem_model (STB_LOCAL)
ffffffff81f04112-ffffffff81f0413a: __xdp_reg_mem_model.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct xdp_mem_allocator *__xdp_reg_mem_model(struct xdp_mem_info *mem, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/xdp.c (0)
Location: net/core/xdp.c:270
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:xdp_reg_mem_model
```
**Symbols:**

```
ffffffff81e05f60-ffffffff81e0622e: __xdp_reg_mem_model (STB_LOCAL)
ffffffff820ac7ff-ffffffff820ac827: __xdp_reg_mem_model.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct xdp_mem_allocator *__xdp_reg_mem_model(struct xdp_mem_info *mem, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/xdp.c (0)
Location: net/core/xdp.c:272
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:xdp_reg_mem_model
```
**Symbols:**

```
ffffffff81e786a0-ffffffff81e78966: __xdp_reg_mem_model (STB_LOCAL)
ffffffff8212de94-ffffffff8212debc: __xdp_reg_mem_model.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct xdp_mem_allocator *__xdp_reg_mem_model(struct xdp_mem_info *mem, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/xdp.c (0)
Location: net/core/xdp.c:272
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:xdp_reg_mem_model
```
**Symbols:**

```
ffffffff81f38510-ffffffff81f38834: __xdp_reg_mem_model (STB_LOCAL)
ffffffff8220fc20-ffffffff8220fc48: __xdp_reg_mem_model.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
