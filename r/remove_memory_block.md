# Function: <code>remove_memory_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81561a89)
Location: drivers/base/memory.c:695
Inline: True
Inline callers:
  - drivers/base/memory.c:unregister_memory_section
```
</details>
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
void remove_memory_block(struct memory_block *memory);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff819a3c50)
Location: drivers/base/memory.c:789
Inline: False
Direct callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff819a3c50-ffffffff819a3d04: remove_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void remove_memory_block(struct memory_block *memory);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b15be0)
Location: drivers/base/memory.c:801
Inline: False
Direct callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff81b15be0-ffffffff81b15c94: remove_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void remove_memory_block(struct memory_block *memory);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b64950)
Location: drivers/base/memory.c:796
Inline: False
Direct callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff81b64950-ffffffff81b64a04: remove_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void remove_memory_block(struct memory_block *memory);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81bb83d0)
Location: drivers/base/memory.c:846
Inline: False
Direct callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff81bb83d0-ffffffff81bb8484: remove_memory_block (STB_LOCAL)
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
