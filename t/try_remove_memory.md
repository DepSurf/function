# Function: <code>try_remove_memory</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int try_remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a91520)
Location: mm/memory_hotplug.c:1767
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:__remove_memory
```
**Symbols:**

```
ffffffff81a91520-ffffffff81a91652: try_remove_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int try_remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ac8850)
Location: mm/memory_hotplug.c:1754
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:__remove_memory
```
**Symbols:**

```
ffffffff81ac8850-ffffffff81ac8986: try_remove_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int try_remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81bc1250)
Location: mm/memory_hotplug.c:1760
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:__remove_memory
```
**Symbols:**

```
ffffffff81bc1250-ffffffff81bc1370: try_remove_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int try_remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c3a3e0)
Location: mm/memory_hotplug.c:1722
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:__remove_memory
```
**Symbols:**

```
ffffffff81c3a3e0-ffffffff81c3a4a7: try_remove_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int try_remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c2c910)
Location: mm/memory_hotplug.c:1978
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:__remove_memory
```
**Symbols:**

```
ffffffff81c2c910-ffffffff81c2ca81: try_remove_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int try_remove_memory(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81d4b050)
Location: mm/memory_hotplug.c:2146
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:__remove_memory
```
**Symbols:**

```
ffffffff81d4b050-ffffffff81d4b1e6: try_remove_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int try_remove_memory(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81f1a910)
Location: mm/memory_hotplug.c:2068
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:__remove_memory
```
**Symbols:**

```
ffffffff81f1a910-ffffffff81f1aab3: try_remove_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int try_remove_memory(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff820c27b0)
Location: mm/memory_hotplug.c:2064
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:__remove_memory
```
**Symbols:**

```
ffffffff820c27b0-ffffffff820c2953: try_remove_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int try_remove_memory(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff82146550)
Location: mm/memory_hotplug.c:2037
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:__remove_memory
```
**Symbols:**

```
ffffffff82146550-ffffffff821466f3: try_remove_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int try_remove_memory(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff82228d20)
Location: mm/memory_hotplug.c:2249
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:__remove_memory
```
**Symbols:**

```
ffffffff82228d20-ffffffff82228e8d: try_remove_memory (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int try_remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042f150)
Location: mm/memory_hotplug.c:1754
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:__remove_memory
```
**Symbols:**

```
c00000000042f150-c00000000042f2fc: try_remove_memory (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int try_remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a676c0)
Location: mm/memory_hotplug.c:1754
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:__remove_memory
```
**Symbols:**

```
ffffffff81a676c0-ffffffff81a677f6: try_remove_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int try_remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a24180)
Location: mm/memory_hotplug.c:1754
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:__remove_memory
```
**Symbols:**

```
ffffffff81a24180-ffffffff81a242b6: try_remove_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int try_remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ad3ad0)
Location: mm/memory_hotplug.c:1754
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:__remove_memory
```
**Symbols:**

```
ffffffff81ad3ad0-ffffffff81ad3c06: try_remove_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int try_remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81adffc0)
Location: mm/memory_hotplug.c:1754
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:__remove_memory
```
**Symbols:**

```
ffffffff81adffc0-ffffffff81ae00f6: try_remove_memory (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nid</code>
</li>
<li>
<b>Param reordered. </b>
<code>nid, start, size</code> ➡️ <code>start, size</code>
</li>
</ul>
</details>
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
