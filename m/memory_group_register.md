# Function: <code>memory_group_register</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int memory_group_register(struct memory_group group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:923
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_group_register_dynamic
  - drivers/base/memory.c:memory_group_register_static
```
**Symbols:**

```
ffffffff8185cd40-ffffffff8185ce79: memory_group_register (STB_LOCAL)
ffffffff81d04456-ffffffff81d0446b: memory_group_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int memory_group_register(struct memory_group group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:1019
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_group_register_dynamic
  - drivers/base/memory.c:memory_group_register_static
```
**Symbols:**

```
ffffffff819a3fc0-ffffffff819a4100: memory_group_register (STB_LOCAL)
ffffffff81eccdf2-ffffffff81ecce06: memory_group_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int memory_group_register(struct memory_group group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:1026
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_group_register_dynamic
  - drivers/base/memory.c:memory_group_register_static
```
**Symbols:**

```
ffffffff81b15fa0-ffffffff81b160e5: memory_group_register (STB_LOCAL)
ffffffff82098bc1-ffffffff82098bd5: memory_group_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int memory_group_register(struct memory_group group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:1021
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_group_register_dynamic
  - drivers/base/memory.c:memory_group_register_static
```
**Symbols:**

```
ffffffff81b64d10-ffffffff81b64e55: memory_group_register (STB_LOCAL)
ffffffff82119b8d-ffffffff82119ba1: memory_group_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int memory_group_register(struct memory_group group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:1074
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_group_register_dynamic
  - drivers/base/memory.c:memory_group_register_static
```
**Symbols:**

```
ffffffff81bb8a40-ffffffff81bb8bb4: memory_group_register (STB_LOCAL)
ffffffff821f7a95-ffffffff821f7aa9: memory_group_register.cold (STB_LOCAL)
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
