# Function: <code>memory_block_online</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int memory_block_online(struct memory_block *mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d1b90)
Location: drivers/base/memory.c:172
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_online
```
**Symbols:**

```
ffffffff817d1b90-ffffffff817d1c4b: memory_block_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int memory_block_online(struct memory_block *mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8185c950)
Location: drivers/base/memory.c:178
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_online
```
**Symbols:**

```
ffffffff8185c950-ffffffff8185ca3c: memory_block_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int memory_block_online(struct memory_block *mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff819a3b50)
Location: drivers/base/memory.c:178
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_online
```
**Symbols:**

```
ffffffff819a3b50-ffffffff819a3c4e: memory_block_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int memory_block_online(struct memory_block *mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b15ac0)
Location: drivers/base/memory.c:187
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_online
```
**Symbols:**

```
ffffffff81b15ac0-ffffffff81b15bd0: memory_block_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int memory_block_online(struct memory_block *mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b64830)
Location: drivers/base/memory.c:182
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_online
```
**Symbols:**

```
ffffffff81b64830-ffffffff81b64940: memory_block_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int memory_block_online(struct memory_block *mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:186
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_online
```
**Symbols:**

```
ffffffff81bb87e0-ffffffff81bb8a24: memory_block_online (STB_LOCAL)
ffffffff821f7a7a-ffffffff821f7a95: memory_block_online.cold (STB_LOCAL)
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
