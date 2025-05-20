# Function: <code>xbc_node_find_child</code>

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
struct xbc_node *xbc_node_find_child(struct xbc_node *parent, const char *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82d0a1e6)
Location: lib/bootconfig.c:154
Inline: False
Direct callers:
  - init/main.c:xbc_make_cmdline
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_instances
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - lib/bootconfig.c:xbc_node_find_value
```
**Symbols:**

```
ffffffff82d0a1e6-ffffffff82d0a247: xbc_node_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xbc_node *xbc_node_find_child(struct xbc_node *parent, const char *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82ff77cd)
Location: lib/bootconfig.c:154
Inline: False
Direct callers:
  - init/main.c:xbc_make_cmdline
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_instances
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - lib/bootconfig.c:xbc_node_find_value
```
**Symbols:**

```
ffffffff82ff77cd-ffffffff82ff782e: xbc_node_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xbc_node *xbc_node_find_child(struct xbc_node *parent, const char *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff832022ad)
Location: lib/bootconfig.c:154
Inline: False
Direct callers:
  - init/main.c:xbc_make_cmdline
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - lib/bootconfig.c:xbc_node_find_value
```
**Symbols:**

```
ffffffff832022ad-ffffffff8320233d: xbc_node_find_child (STB_GLOBAL)
```
</details>
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
</ul>
