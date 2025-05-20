# Function: <code>__try_online_node</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __try_online_node(int nid, u64 start, bool set_node_online);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8128038c)
Location: mm/memory_hotplug.c:1028
Inline: True
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff81280300-ffffffff812803a7: __try_online_node (STB_LOCAL)
ffffffff81281149-ffffffff81281161: __try_online_node.cold.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __try_online_node(int nid, u64 start, bool set_node_online);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8129c6cf)
Location: mm/memory_hotplug.c:1009
Inline: True
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff8129c640-ffffffff8129c6eb: __try_online_node (STB_LOCAL)
ffffffff8129d501-ffffffff8129d51a: __try_online_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __try_online_node(int nid, u64 start, bool set_node_online);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812ac36f)
Location: mm/memory_hotplug.c:984
Inline: True
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff812ac2e0-ffffffff812ac38b: __try_online_node (STB_LOCAL)
ffffffff812acc7b-ffffffff812acc94: __try_online_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81bc1bff)
Location: mm/memory_hotplug.c:966
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
Direct callers:
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff812e0ca0-ffffffff812e0d2a: __try_online_node.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c3acad)
Location: mm/memory_hotplug.c:971
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
Direct callers:
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff812ebaa0-ffffffff812ebb26: __try_online_node.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __try_online_node(int nid, bool set_node_online);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812c629b)
Location: mm/memory_hotplug.c:1099
Inline: True
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff812c6250-ffffffff812c6306: __try_online_node (STB_LOCAL)
ffffffff81bda492-ffffffff81bda4ab: __try_online_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __try_online_node(int nid, bool set_node_online);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8130b08b)
Location: mm/memory_hotplug.c:1255
Inline: True
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff8130b040-ffffffff8130b0f6: __try_online_node (STB_LOCAL)
ffffffff81cbe64d-ffffffff81cbe666: __try_online_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __try_online_node(int nid, bool set_node_online);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81373a31)
Location: mm/memory_hotplug.c:1221
Inline: True
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff813739e0-ffffffff81373a94: __try_online_node (STB_LOCAL)
ffffffff81e70640-ffffffff81e70659: __try_online_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __try_online_node(int nid, bool set_node_online);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f15a0)
Location: mm/memory_hotplug.c:1219
Inline: True
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff813f15a0-ffffffff813f1669: __try_online_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __try_online_node(int nid, bool set_node_online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff814250e0)
Location: mm/memory_hotplug.c:1194
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff814250e0-ffffffff814251aa: __try_online_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __try_online_node(int nid, bool set_node_online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81452320)
Location: mm/memory_hotplug.c:1272
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff81452320-ffffffff814523ea: __try_online_node (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __try_online_node(int nid, u64 start, bool set_node_online);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffff80001034db38)
Location: mm/memory_hotplug.c:984
Inline: True
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffff80001034db38-ffff80001034dc54: __try_online_node (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __try_online_node(int nid, u64 start, bool set_node_online);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042dc00)
Location: mm/memory_hotplug.c:984
Inline: True
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
c00000000042dc00-c00000000042ddd4: __try_online_node (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __try_online_node(int nid, u64 start, bool set_node_online);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a494f)
Location: mm/memory_hotplug.c:984
Inline: True
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff812a48c0-ffffffff812a496b: __try_online_node (STB_LOCAL)
ffffffff812a525b-ffffffff812a5274: __try_online_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __try_online_node(int nid, u64 start, bool set_node_online);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8129641f)
Location: mm/memory_hotplug.c:984
Inline: True
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff81296390-ffffffff8129643b: __try_online_node (STB_LOCAL)
ffffffff81296d2b-ffffffff81296d44: __try_online_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __try_online_node(int nid, u64 start, bool set_node_online);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a275f)
Location: mm/memory_hotplug.c:984
Inline: True
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff812a26d0-ffffffff812a277b: __try_online_node (STB_LOCAL)
ffffffff812a306b-ffffffff812a3084: __try_online_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __try_online_node(int nid, u64 start, bool set_node_online);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812b2abf)
Location: mm/memory_hotplug.c:984
Inline: True
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff812b2a30-ffffffff812b2adb: __try_online_node (STB_LOCAL)
ffffffff812b32fb-ffffffff812b3314: __try_online_node.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
