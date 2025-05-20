# Function: <code>walk_dynamic_memory_groups</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int walk_dynamic_memory_groups(int nid, walk_memory_groups_func_t func, struct memory_group *excluded, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8185d9a0)
Location: drivers/base/memory.c:1056
Inline: False
Direct callers:
  - mm/memory_hotplug.c:auto_movable_can_online_movable
  - mm/memory_hotplug.c:auto_movable_can_online_movable
```
**Symbols:**

```
ffffffff8185d9a0-ffffffff8185da5b: walk_dynamic_memory_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int walk_dynamic_memory_groups(int nid, walk_memory_groups_func_t func, struct memory_group *excluded, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff819a4e20)
Location: drivers/base/memory.c:1152
Inline: False
Direct callers:
  - mm/memory_hotplug.c:auto_movable_can_online_movable
  - mm/memory_hotplug.c:auto_movable_can_online_movable
```
**Symbols:**

```
ffffffff819a4e20-ffffffff819a4ee5: walk_dynamic_memory_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int walk_dynamic_memory_groups(int nid, walk_memory_groups_func_t func, struct memory_group *excluded, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b16f40)
Location: drivers/base/memory.c:1159
Inline: False
Direct callers:
  - mm/memory_hotplug.c:auto_movable_can_online_movable
  - mm/memory_hotplug.c:auto_movable_can_online_movable
```
**Symbols:**

```
ffffffff81b16f40-ffffffff81b17005: walk_dynamic_memory_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int walk_dynamic_memory_groups(int nid, walk_memory_groups_func_t func, struct memory_group *excluded, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b65cb0)
Location: drivers/base/memory.c:1154
Inline: False
Direct callers:
  - mm/memory_hotplug.c:auto_movable_can_online_movable
  - mm/memory_hotplug.c:auto_movable_can_online_movable
```
**Symbols:**

```
ffffffff81b65cb0-ffffffff81b65d75: walk_dynamic_memory_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int walk_dynamic_memory_groups(int nid, walk_memory_groups_func_t func, struct memory_group *excluded, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81bb9b30)
Location: drivers/base/memory.c:1207
Inline: False
Direct callers:
  - mm/memory_hotplug.c:auto_movable_can_online_movable
  - mm/memory_hotplug.c:auto_movable_can_online_movable
```
**Symbols:**

```
ffffffff81bb9b30-ffffffff81bb9bf5: walk_dynamic_memory_groups (STB_GLOBAL)
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
