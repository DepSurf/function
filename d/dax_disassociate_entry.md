# Function: <code>dax_disassociate_entry</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812f5ce0)
Location: fs/dax.c:365
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:__dax_invalidate_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff812f5ce0-ffffffff812f5d6a: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130add0)
Location: fs/dax.c:344
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8130add0-ffffffff8130ae5e: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81333160)
Location: fs/dax.c:349
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff81333160-ffffffff813331f0: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81346d10)
Location: fs/dax.c:350
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff81346d10-ffffffff81346da0: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138ca80)
Location: fs/dax.c:350
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8138ca80-ffffffff8138cb16: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8139e210)
Location: fs/dax.c:350
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8139e210-ffffffff8139e2a6: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a52d0)
Location: fs/dax.c:361
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff813a52d0-ffffffff813a5366: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f4ba0)
Location: fs/dax.c:361
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff813f4ba0-ffffffff813f4c36: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814679f0)
Location: fs/dax.c:361
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff814679f0-ffffffff81467aa0: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814f8630)
Location: fs/dax.c:393
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff814f8630-ffffffff814f86ef: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8152f4c0)
Location: fs/dax.c:393
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8152f4c0-ffffffff8152f57f: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff815643a0)
Location: fs/dax.c:379
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff815643a0-ffffffff8156445f: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffff8000104070c8)
Location: fs/dax.c:350
Inline: False
Direct callers:
  - fs/dax.c:__dax_invalidate_entry
```
**Symbols:**

```
ffff8000104070c8-ffff800010407170: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (c000000000512f90)
Location: fs/dax.c:350
Inline: False
Direct callers:
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
c000000000512f90-c000000000513080: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffe0002b2038)
Location: fs/dax.c:350
Inline: False
Direct callers:
  - fs/dax.c:__dax_invalidate_entry
```
**Symbols:**

```
ffffffe0002b2038-ffffffe0002b20c2: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133f2f0)
Location: fs/dax.c:350
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8133f2f0-ffffffff8133f380: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8132ffb0)
Location: fs/dax.c:350
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8132ffb0-ffffffff81330040: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133cdc0)
Location: fs/dax.c:350
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8133cdc0-ffffffff8133ce50: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dax_disassociate_entry(void *entry, struct address_space *mapping, bool trunc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81350050)
Location: fs/dax.c:350
Inline: False
Direct callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff81350050-ffffffff813500e0: dax_disassociate_entry (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
