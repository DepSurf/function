# Function: <code>genl_op_iter_next</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool genl_op_iter_next(struct genl_op_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81e6d780)
Location: net/netlink/genetlink.c:335
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:genl_validate_ops
  - net/netlink/genetlink.c:genl_validate_ops
```
**Symbols:**

```
ffffffff81e6d780-ffffffff81e6d89d: genl_op_iter_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool genl_op_iter_next(struct genl_op_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81ec9890)
Location: net/netlink/genetlink.c:335
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:genl_validate_ops
  - net/netlink/genetlink.c:genl_validate_ops
```
**Symbols:**

```
ffffffff81ec9890-ffffffff81ec99ad: genl_op_iter_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool genl_op_iter_next(struct genl_op_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81f8c960)
Location: net/netlink/genetlink.c:348
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_fill_info
  - net/netlink/genetlink.c:genl_validate_ops
  - net/netlink/genetlink.c:genl_validate_ops
```
**Symbols:**

```
ffffffff81f8c960-ffffffff81f8ca7d: genl_op_iter_next (STB_LOCAL)
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
