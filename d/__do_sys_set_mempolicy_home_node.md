# Function: <code>__do_sys_set_mempolicy_home_node</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_set_mempolicy_home_node(long unsigned int start, long unsigned int len, long unsigned int home_node, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81399a80)
Location: mm/mempolicy.c:1473
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_set_mempolicy_home_node
  - mm/mempolicy.c:__x64_sys_set_mempolicy_home_node
```
**Symbols:**

```
ffffffff81399a80-ffffffff81399c5d: __do_sys_set_mempolicy_home_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_set_mempolicy_home_node(long unsigned int start, long unsigned int len, long unsigned int home_node, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814199a0)
Location: mm/mempolicy.c:1488
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_set_mempolicy_home_node
  - mm/mempolicy.c:__x64_sys_set_mempolicy_home_node
```
**Symbols:**

```
ffffffff814199a0-ffffffff81419bdf: __do_sys_set_mempolicy_home_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_set_mempolicy_home_node(long unsigned int start, long unsigned int len, long unsigned int home_node, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144ce00)
Location: mm/mempolicy.c:1505
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_set_mempolicy_home_node
  - mm/mempolicy.c:__x64_sys_set_mempolicy_home_node
```
**Symbols:**

```
ffffffff8144ce00-ffffffff8144d084: __do_sys_set_mempolicy_home_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_set_mempolicy_home_node(long unsigned int start, long unsigned int len, long unsigned int home_node, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814866f0)
Location: mm/mempolicy.c:1489
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_set_mempolicy_home_node
  - mm/mempolicy.c:__x64_sys_set_mempolicy_home_node
```
**Symbols:**

```
ffffffff814866f0-ffffffff81486984: __do_sys_set_mempolicy_home_node (STB_LOCAL)
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
