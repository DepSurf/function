# Function: <code>genl_op_from_full</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a8544a)
Location: net/netlink/genetlink.c:115
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_get_cmd
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
In net/netlink/genetlink.c (ffffffff81a6e52c)
Location: net/netlink/genetlink.c:115
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_get_cmd
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
In net/netlink/genetlink.c (ffffffff81b27bac)
Location: net/netlink/genetlink.c:107
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_get_cmd
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
In net/netlink/genetlink.c (ffffffff81cb0bdc)
Location: net/netlink/genetlink.c:107
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_get_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void genl_op_from_full(const struct genl_family *family, unsigned int i, struct genl_ops *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81e6cf60)
Location: net/netlink/genetlink.c:142
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_op_iter_next
  - net/netlink/genetlink.c:genl_get_cmd
```
**Symbols:**

```
ffffffff81e6cf60-ffffffff81e6d002: genl_op_from_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void genl_op_from_full(const struct genl_family *family, unsigned int i, struct genl_ops *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81ec9070)
Location: net/netlink/genetlink.c:142
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_op_iter_next
  - net/netlink/genetlink.c:genl_get_cmd
```
**Symbols:**

```
ffffffff81ec9070-ffffffff81ec9112: genl_op_from_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void genl_op_from_full(const struct genl_family *family, unsigned int i, struct genl_ops *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81f8c290)
Location: net/netlink/genetlink.c:154
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_op_iter_next
  - net/netlink/genetlink.c:genl_get_cmd
```
**Symbols:**

```
ffffffff81f8c290-ffffffff81f8c332: genl_op_from_full (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
