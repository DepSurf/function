# Function: <code>mem_id_disconnect</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mem_id_disconnect(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81962b70)
Location: net/core/xdp.c:116
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffff81962b70-ffffffff81962ebe: mem_id_disconnect (STB_LOCAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void mem_id_disconnect(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffff800010c06670)
Location: net/core/xdp.c:116
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffff800010c06670-ffff800010c06a2c: mem_id_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_id_disconnect(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c0d1f744)
Location: net/core/xdp.c:116
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
c0d1f744-c0d1fc60: mem_id_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mem_id_disconnect(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c000000000cf0b90)
Location: net/core/xdp.c:116
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
c000000000cf0b90-c000000000cf103c: mem_id_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mem_id_disconnect(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffe000784bea)
Location: net/core/xdp.c:116
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffe000784bea-ffffffe000784ef8: mem_id_disconnect (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void mem_id_disconnect(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81902b40)
Location: net/core/xdp.c:116
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffff81902b40-ffffffff81902e8e: mem_id_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mem_id_disconnect(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818bc970)
Location: net/core/xdp.c:116
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffff818bc970-ffffffff818bccbe: mem_id_disconnect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mem_id_disconnect(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81953b70)
Location: net/core/xdp.c:116
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffff81953b70-ffffffff81953ebe: mem_id_disconnect (STB_LOCAL)
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
In net/core/xdp.c (ffffffff81975a83)
Location: net/core/xdp.c:116
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
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
</ul>
