# Function: <code>genl_get_cmd_by_index</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void genl_get_cmd_by_index(unsigned int i, const struct genl_family *family, struct genl_ops *op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a84a80)
Location: net/netlink/genetlink.c:177
Inline: True
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:genl_validate_ops
  - net/netlink/genetlink.c:genl_validate_ops
```
**Symbols:**

```
ffffffff81a84a80-ffffffff81a84b08: genl_get_cmd_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void genl_get_cmd_by_index(unsigned int i, const struct genl_family *family, struct genl_ops *op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a6db60)
Location: net/netlink/genetlink.c:177
Inline: True
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_fill_info
```
**Symbols:**

```
ffffffff81a6db60-ffffffff81a6dbe8: genl_get_cmd_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void genl_get_cmd_by_index(unsigned int i, const struct genl_family *family, struct genl_ops *op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81b26d00)
Location: net/netlink/genetlink.c:169
Inline: True
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_fill_info
```
**Symbols:**

```
ffffffff81b26d00-ffffffff81b26d88: genl_get_cmd_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void genl_get_cmd_by_index(unsigned int i, const struct genl_family *family, struct genl_ops *op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81cafac0)
Location: net/netlink/genetlink.c:169
Inline: True
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_fill_info
```
**Symbols:**

```
ffffffff81cafac0-ffffffff81cafb8c: genl_get_cmd_by_index (STB_LOCAL)
```
</details>
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
