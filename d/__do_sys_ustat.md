# Function: <code>__do_sys_ustat</code>

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
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812d4d70)
Location: fs/statfs.c:232
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_ustat
  - fs/statfs.c:__x64_sys_ustat
```
**Symbols:**

```
ffffffff812d4d70-ffffffff812d4e3c: __do_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ea140)
Location: fs/statfs.c:232
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_ustat
  - fs/statfs.c:__x64_sys_ustat
```
**Symbols:**

```
ffffffff812ea140-ffffffff812ea20c: __do_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81308ba0)
Location: fs/statfs.c:246
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_ustat
  - fs/statfs.c:__x64_sys_ustat
```
**Symbols:**

```
ffffffff81308ba0-ffffffff81308c64: __do_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8131bc10)
Location: fs/statfs.c:246
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_ustat
  - fs/statfs.c:__x64_sys_ustat
```
**Symbols:**

```
ffffffff8131bc10-ffffffff8131bcd4: __do_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81355aa0)
Location: fs/statfs.c:246
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_ustat
  - fs/statfs.c:__x64_sys_ustat
```
**Symbols:**

```
ffffffff81355aa0-ffffffff81355b91: __do_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813623e0)
Location: fs/statfs.c:248
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_ustat
  - fs/statfs.c:__x64_sys_ustat
```
**Symbols:**

```
ffffffff813623e0-ffffffff813624d3: __do_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81368e90)
Location: fs/statfs.c:248
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_ustat
  - fs/statfs.c:__x64_sys_ustat
```
**Symbols:**

```
ffffffff81368e90-ffffffff81368f7f: __do_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813b7b90)
Location: fs/statfs.c:248
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_ustat
  - fs/statfs.c:__x64_sys_ustat
```
**Symbols:**

```
ffffffff813b7b90-ffffffff813b7c7f: __do_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8143d2f0)
Location: fs/statfs.c:248
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_ustat
  - fs/statfs.c:__x64_sys_ustat
```
**Symbols:**

```
ffffffff8143d2f0-ffffffff8143d433: __do_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff814cbb00)
Location: fs/statfs.c:248
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_ustat
  - fs/statfs.c:__x64_sys_ustat
```
**Symbols:**

```
ffffffff814cbb00-ffffffff814cbc43: __do_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81501d40)
Location: fs/statfs.c:248
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_ustat
  - fs/statfs.c:__x64_sys_ustat
```
**Symbols:**

```
ffffffff81501d40-ffffffff81501e83: __do_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81536990)
Location: fs/statfs.c:248
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_ustat
  - fs/statfs.c:__x64_sys_ustat
```
**Symbols:**

```
ffffffff81536990-ffffffff81536ad3: __do_sys_ustat (STB_LOCAL)
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
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffff8000103d3760)
Location: fs/statfs.c:246
Inline: False
Direct callers:
  - fs/statfs.c:__arm64_sys_ustat
```
**Symbols:**

```
ffff8000103d3760-ffff8000103d3848: __do_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c05ad940)
Location: fs/statfs.c:246
Inline: False
Direct callers:
  - fs/statfs.c:__se_sys_ustat
```
**Symbols:**

```
c05ad940-c05ada5c: __do_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d5f40)
Location: fs/statfs.c:246
Inline: False
Direct callers:
  - fs/statfs.c:__se_sys_ustat
```
**Symbols:**

```
c0000000004d5f40-c0000000004d6018: __do_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffe00028e11a)
Location: fs/statfs.c:246
Inline: False
Direct callers:
  - fs/statfs.c:__se_sys_ustat
```
**Symbols:**

```
ffffffe00028e11a-ffffffe00028e1ba: __do_sys_ustat (STB_LOCAL)
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
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813141f0)
Location: fs/statfs.c:246
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_ustat
  - fs/statfs.c:__x64_sys_ustat
```
**Symbols:**

```
ffffffff813141f0-ffffffff813142b4: __do_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81304e00)
Location: fs/statfs.c:246
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_ustat
  - fs/statfs.c:__x64_sys_ustat
```
**Symbols:**

```
ffffffff81304e00-ffffffff81304ec4: __do_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81311fe0)
Location: fs/statfs.c:246
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_ustat
  - fs/statfs.c:__x64_sys_ustat
```
**Symbols:**

```
ffffffff81311fe0-ffffffff813120a4: __do_sys_ustat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_sys_ustat(unsigned int dev, struct ustat *ubuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81323820)
Location: fs/statfs.c:246
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_sys_ustat
  - fs/statfs.c:__x64_sys_ustat
```
**Symbols:**

```
ffffffff81323820-ffffffff813238e4: __do_sys_ustat (STB_LOCAL)
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
