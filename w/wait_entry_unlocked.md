# Function: <code>wait_entry_unlocked</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130cb90)
Location: fs/dax.c:240
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_page
```
**Symbols:**

```
ffffffff8130cb90-ffffffff8130cc6e: wait_entry_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81334150)
Location: fs/dax.c:245
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_page
```
**Symbols:**

```
ffffffff81334150-ffffffff8133422a: wait_entry_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81347d10)
Location: fs/dax.c:246
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_page
```
**Symbols:**

```
ffffffff81347d10-ffffffff81347dea: wait_entry_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138d2a0)
Location: fs/dax.c:246
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_page
```
**Symbols:**

```
ffffffff8138d2a0-ffffffff8138d37a: wait_entry_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8139ea30)
Location: fs/dax.c:246
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_page
```
**Symbols:**

```
ffffffff8139ea30-ffffffff8139eb0a: wait_entry_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a5b20)
Location: fs/dax.c:257
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_page
```
**Symbols:**

```
ffffffff813a5b20-ffffffff813a5bfa: wait_entry_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f5590)
Location: fs/dax.c:257
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_page
```
**Symbols:**

```
ffffffff813f5590-ffffffff813f566a: wait_entry_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814676c0)
Location: fs/dax.c:257
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_page
```
**Symbols:**

```
ffffffff814676c0-ffffffff814677a9: wait_entry_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814f79d0)
Location: fs/dax.c:257
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_page
```
**Symbols:**

```
ffffffff814f79d0-ffffffff814f7ab9: wait_entry_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8152e820)
Location: fs/dax.c:257
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_page
```
**Symbols:**

```
ffffffff8152e820-ffffffff8152e909: wait_entry_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81563700)
Location: fs/dax.c:243
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_folio
```
**Symbols:**

```
ffffffff81563700-ffffffff815637e9: wait_entry_unlocked (STB_LOCAL)
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
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffff8000104087d8)
Location: fs/dax.c:246
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_page
```
**Symbols:**

```
ffff8000104087d8-ffff8000104088c8: wait_entry_unlocked (STB_LOCAL)
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
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (c000000000513da0)
Location: fs/dax.c:246
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_page
```
**Symbols:**

```
c000000000513da0-c000000000513f18: wait_entry_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffe0002b2b04)
Location: fs/dax.c:246
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_page
```
**Symbols:**

```
ffffffe0002b2b04-ffffffe0002b2bf8: wait_entry_unlocked (STB_LOCAL)
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
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813402f0)
Location: fs/dax.c:246
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_page
```
**Symbols:**

```
ffffffff813402f0-ffffffff813403ca: wait_entry_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81330f70)
Location: fs/dax.c:246
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_page
```
**Symbols:**

```
ffffffff81330f70-ffffffff81331044: wait_entry_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133ddc0)
Location: fs/dax.c:246
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_page
```
**Symbols:**

```
ffffffff8133ddc0-ffffffff8133de9a: wait_entry_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wait_entry_unlocked(struct xa_state *xas, void *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8134ff70)
Location: fs/dax.c:246
Inline: False
Direct callers:
  - fs/dax.c:dax_lock_page
```
**Symbols:**

```
ffffffff8134ff70-ffffffff81350041: wait_entry_unlocked (STB_LOCAL)
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
