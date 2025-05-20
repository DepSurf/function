# Function: <code>vm_commit_limit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811ac190)
Location: mm/util.c:379
Inline: False
Direct callers:
  - mm/mmap.c:__vm_enough_memory
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff811ac190-ffffffff811ac1f7: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811c4db0)
Location: mm/util.c:463
Inline: False
Direct callers:
  - mm/util.c:__vm_enough_memory
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff811c4db0-ffffffff811c4e17: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811d4ec0)
Location: mm/util.c:466
Inline: False
Direct callers:
  - mm/util.c:__vm_enough_memory
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff811d4ec0-ffffffff811d4f27: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811ddd10)
Location: mm/util.c:550
Inline: False
Direct callers:
  - mm/util.c:__vm_enough_memory
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff811ddd10-ffffffff811ddd77: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f3790)
Location: mm/util.c:550
Inline: False
Direct callers:
  - mm/util.c:__vm_enough_memory
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff811f3790-ffffffff811f37f7: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81214aa0)
Location: mm/util.c:586
Inline: False
Direct callers:
  - mm/util.c:__vm_enough_memory
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff81214aa0-ffffffff81214b07: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81227980)
Location: mm/util.c:589
Inline: False
Direct callers:
  - mm/util.c:__vm_enough_memory
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff81227980-ffffffff812279e7: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81237720)
Location: mm/util.c:632
Inline: False
Direct callers:
  - mm/util.c:__vm_enough_memory
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff81237720-ffffffff81237787: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81245970)
Location: mm/util.c:737
Inline: False
Direct callers:
  - mm/util.c:__vm_enough_memory
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff81245970-ffffffff812459d7: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81273768)
Location: mm/util.c:763
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
Direct callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff812736a0-ffffffff81273704: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127dff8)
Location: mm/util.c:817
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
Direct callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff8127df30-ffffffff8127df94: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81283168)
Location: mm/util.c:807
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
Direct callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff812830a0-ffffffff81283107: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c1328)
Location: mm/util.c:838
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
Direct callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff812c1260-ffffffff812c12c7: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131e314)
Location: mm/util.c:963
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
Direct callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff8131e240-ffffffff8131e2b0: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81391d88)
Location: mm/util.c:856
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
Direct callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff81391ca0-ffffffff81391d10: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c4788)
Location: mm/util.c:879
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
Direct callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff813c46a0-ffffffff813c4710: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813ef208)
Location: mm/util.c:887
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
Direct callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff813ef120-ffffffff813ef190: vm_commit_limit (STB_GLOBAL)
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
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d8fb8)
Location: mm/util.c:737
Inline: False
Direct callers:
  - mm/util.c:__vm_enough_memory
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffff8000102d8fb8-ffff8000102d9044: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/util.c (c0500224)
Location: mm/util.c:737
Inline: True
Inline callers:
  - mm/util.c:__vm_enough_memory
Direct callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
c0500154-c05001b4: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c000000000398ab0)
Location: mm/util.c:737
Inline: False
Direct callers:
  - mm/util.c:__vm_enough_memory
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
c000000000398ab0-c000000000398b68: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f33fc)
Location: mm/util.c:737
Inline: False
Direct callers:
  - mm/util.c:__vm_enough_memory
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffe0001f33fc-ffffffe0001f346c: vm_commit_limit (STB_GLOBAL)
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
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123dfc0)
Location: mm/util.c:737
Inline: False
Direct callers:
  - mm/util.c:__vm_enough_memory
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff8123dfc0-ffffffff8123e027: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81230fc0)
Location: mm/util.c:737
Inline: False
Direct callers:
  - mm/util.c:__vm_enough_memory
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff81230fc0-ffffffff81231027: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123bd60)
Location: mm/util.c:737
Inline: False
Direct callers:
  - mm/util.c:__vm_enough_memory
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff8123bd60-ffffffff8123bdc7: vm_commit_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int vm_commit_limit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124b470)
Location: mm/util.c:737
Inline: False
Direct callers:
  - mm/util.c:__vm_enough_memory
  - fs/proc/meminfo.c:meminfo_proc_show
```
**Symbols:**

```
ffffffff8124b470-ffffffff8124b4d7: vm_commit_limit (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
