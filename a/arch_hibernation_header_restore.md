# Function: <code>arch_hibernation_header_restore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate_64.c (ffffffff816fb480)
Location: arch/x86/power/hibernate_64.c:140
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff816fb480-ffffffff816fb4bb: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate_64.c (ffffffff81760a70)
Location: arch/x86/power/hibernate_64.c:212
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff81760a70-ffffffff81760ab6: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate_64.c (ffffffff8178dbf0)
Location: arch/x86/power/hibernate_64.c:291
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff8178dbf0-ffffffff8178dcd0: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate_64.c (ffffffff817abd90)
Location: arch/x86/power/hibernate_64.c:311
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff817abd90-ffffffff817abe79: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate_64.c (ffffffff81823370)
Location: arch/x86/power/hibernate_64.c:330
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff81823370-ffffffff81823459: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate_64.c (0)
Location: arch/x86/power/hibernate_64.c:340
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff8186d706-ffffffff8186d71c: arch_hibernation_header_restore.cold.7 (STB_LOCAL)
ffffffff8186d630-ffffffff8186d706: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/power/hibernate.c:190
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff8188f517-ffffffff8188f52d: arch_hibernation_header_restore.cold.6 (STB_LOCAL)
ffffffff8188f1f0-ffffffff8188f2c6: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/power/hibernate.c:190
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff818d9578-ffffffff818d95a4: arch_hibernation_header_restore.cold (STB_LOCAL)
ffffffff818d9200-ffffffff818d92cf: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/power/hibernate.c:190
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff8190b578-ffffffff8190b5a4: arch_hibernation_header_restore.cold (STB_LOCAL)
ffffffff8190b200-ffffffff8190b2cf: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/power/hibernate.c:190
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff81bbc5c8-ffffffff81bbc5f4: arch_hibernation_header_restore.cold (STB_LOCAL)
ffffffff81bbc220-ffffffff81bbc2ed: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/power/hibernate.c:190
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff81c34c2e-ffffffff81c34c5a: arch_hibernation_header_restore.cold (STB_LOCAL)
ffffffff81bd1200-ffffffff81bd12cd: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/power/hibernate.c:129
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff81c27016-ffffffff81c27042: arch_hibernation_header_restore.cold (STB_LOCAL)
ffffffff81bc3290-ffffffff81bc3305: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/power/hibernate.c:129
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff81d4503a-ffffffff81d45066: arch_hibernation_header_restore.cold (STB_LOCAL)
ffffffff81c94290-ffffffff81c94305: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/power/hibernate.c:129
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff81f11f13-ffffffff81f11f3f: arch_hibernation_header_restore.cold (STB_LOCAL)
ffffffff81e432c0-ffffffff81e4333f: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate.c (ffffffff8201e350)
Location: arch/x86/power/hibernate.c:129
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff8201e350-ffffffff8201e3ed: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate.c (ffffffff8209e350)
Location: arch/x86/power/hibernate.c:129
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff8209e350-ffffffff8209e3ed: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate.c (ffffffff82176350)
Location: arch/x86/power/hibernate.c:129
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff82176350-ffffffff821763ed: arch_hibernation_header_restore (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/power/hibernate.c:190
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff818ab578-ffffffff818ab5a4: arch_hibernation_header_restore.cold (STB_LOCAL)
ffffffff818ab200-ffffffff818ab2cf: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/power/hibernate.c:190
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff818654c8-ffffffff818654f4: arch_hibernation_header_restore.cold (STB_LOCAL)
ffffffff81865200-ffffffff818652cf: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/power/hibernate.c:190
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff818fc578-ffffffff818fc5a4: arch_hibernation_header_restore.cold (STB_LOCAL)
ffffffff818fc200-ffffffff818fc2cf: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int arch_hibernation_header_restore(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/power/hibernate.c:190
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff8191d578-ffffffff8191d5a4: arch_hibernation_header_restore.cold (STB_LOCAL)
ffffffff8191d200-ffffffff8191d2cf: arch_hibernation_header_restore (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
