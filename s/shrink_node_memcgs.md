# Function: <code>shrink_node_memcgs</code>

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
void shrink_node_memcgs(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812688e0)
Location: mm/vmscan.c:2611
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff812688e0-ffffffff81268a6f: shrink_node_memcgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void shrink_node_memcgs(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81273360)
Location: mm/vmscan.c:2619
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff81273360-ffffffff8127352b: shrink_node_memcgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void shrink_node_memcgs(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81278680)
Location: mm/vmscan.c:2817
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff81278680-ffffffff8127884b: shrink_node_memcgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void shrink_node_memcgs(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b63e0)
Location: mm/vmscan.c:2972
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff812b63e0-ffffffff812b65a2: shrink_node_memcgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void shrink_node_memcgs(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81311880)
Location: mm/vmscan.c:3078
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff81311880-ffffffff81311a4a: shrink_node_memcgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void shrink_node_memcgs(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81384e90)
Location: mm/vmscan.c:6101
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff81384e90-ffffffff81385084: shrink_node_memcgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void shrink_node_memcgs(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b69f0)
Location: mm/vmscan.c:6459
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff813b69f0-ffffffff813b6be4: shrink_node_memcgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void shrink_node_memcgs(pg_data_t *pgdat, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813df8b0)
Location: mm/vmscan.c:5823
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff813df8b0-ffffffff813dfaa4: shrink_node_memcgs (STB_LOCAL)
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
