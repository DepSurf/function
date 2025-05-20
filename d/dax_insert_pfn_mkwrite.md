# Function: <code>dax_insert_pfn_mkwrite</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812cd934)
Location: fs/dax.c:1522
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812f80b4)
Location: fs/dax.c:1745
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130e950)
Location: fs/dax.c:1650
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813350a4)
Location: fs/dax.c:1666
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81348c84)
Location: fs/dax.c:1670
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t dax_insert_pfn_mkwrite(struct vm_fault *vmf, pfn_t pfn, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138eed0)
Location: fs/dax.c:1660
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff8138eed0-ffffffff8138f13a: dax_insert_pfn_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t dax_insert_pfn_mkwrite(struct vm_fault *vmf, pfn_t pfn, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a0590)
Location: fs/dax.c:1675
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff813a0590-ffffffff813a07c4: dax_insert_pfn_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t dax_insert_pfn_mkwrite(struct vm_fault *vmf, pfn_t pfn, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a6cd0)
Location: fs/dax.c:1687
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff813a6cd0-ffffffff813a6f07: dax_insert_pfn_mkwrite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
vm_fault_t dax_insert_pfn_mkwrite(struct vm_fault *vmf, pfn_t pfn, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1659
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff813f6b80-ffffffff813f6dc2: dax_insert_pfn_mkwrite (STB_LOCAL)
ffffffff81cc6054-ffffffff81cc6090: dax_insert_pfn_mkwrite.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
vm_fault_t dax_insert_pfn_mkwrite(struct vm_fault *vmf, pfn_t pfn, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1619
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff81469750-ffffffff814699de: dax_insert_pfn_mkwrite (STB_LOCAL)
ffffffff81e78296-ffffffff81e782d2: dax_insert_pfn_mkwrite.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
vm_fault_t dax_insert_pfn_mkwrite(struct vm_fault *vmf, pfn_t pfn, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1903
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff814fa520-ffffffff814fa7ad: dax_insert_pfn_mkwrite (STB_LOCAL)
ffffffff8206a1ad-ffffffff8206a1e9: dax_insert_pfn_mkwrite.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
vm_fault_t dax_insert_pfn_mkwrite(struct vm_fault *vmf, pfn_t pfn, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1945
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff81531990-ffffffff81531c0f: dax_insert_pfn_mkwrite (STB_LOCAL)
ffffffff820ea192-ffffffff820ea1c3: dax_insert_pfn_mkwrite.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
vm_fault_t dax_insert_pfn_mkwrite(struct vm_fault *vmf, pfn_t pfn, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1929
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
```
**Symbols:**

```
ffffffff81566870-ffffffff81566af3: dax_insert_pfn_mkwrite (STB_LOCAL)
ffffffff821c6c37-ffffffff821c6c65: dax_insert_pfn_mkwrite.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffff80001040912c)
Location: fs/dax.c:1670
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (c000000000515518)
Location: fs/dax.c:1670
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffe0002b347c)
Location: fs/dax.c:1670
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81341264)
Location: fs/dax.c:1670
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81331c34)
Location: fs/dax.c:1670
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133ed34)
Location: fs/dax.c:1670
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81351116)
Location: fs/dax.c:1670
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
```
</details>
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
