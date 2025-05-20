# Function: <code>__fput_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff8120e6f0)
Location: fs/file_table.c:294
Inline: False
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff8120e6f0-ffffffff8120e719: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812350f0)
Location: fs/file_table.c:295
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff812350f0-ffffffff81235119: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81247c90)
Location: fs/file_table.c:295
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff81247c90-ffffffff81247cb9: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812534b0)
Location: fs/file_table.c:297
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff812534b0-ffffffff812534da: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812755b0)
Location: fs/file_table.c:295
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff812755b0-ffffffff812755d8: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff8129be50)
Location: fs/file_table.c:294
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff8129be50-ffffffff8129be78: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812b0de0)
Location: fs/file_table.c:360
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff812b0de0-ffffffff812b0e08: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812cd760)
Location: fs/file_table.c:369
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff812cd760-ffffffff812cd789: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812df180)
Location: fs/file_table.c:369
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff812df180-ffffffff812df1a9: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81315fb0)
Location: fs/file_table.c:370
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff81315fb0-ffffffff81315fd9: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81321570)
Location: fs/file_table.c:369
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff81321570-ffffffff81321599: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81327760)
Location: fs/file_table.c:368
Inline: False
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff81327760-ffffffff81327789: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81374bb0)
Location: fs/file_table.c:369
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff81374bb0-ffffffff81374bd9: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff813f39d0)
Location: fs/file_table.c:400
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff813f39d0-ffffffff813f3a09: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff8147c7d0)
Location: fs/file_table.c:398
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff8147c7d0-ffffffff8147c809: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff814b13a0)
Location: fs/file_table.c:462
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff814b13a0-ffffffff814b13d9: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff814e2bf0)
Location: fs/file_table.c:458
Inline: False
Direct callers:
  - kernel/acct.c:close_work
  - fs/open.c:__ia32_sys_close
  - fs/open.c:__x64_sys_close
```
**Symbols:**

```
ffffffff814e2bf0-ffffffff814e2c14: __fput_sync (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffff800010385700)
Location: fs/file_table.c:369
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffff800010385700-ffff80001038576c: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (c056e7a8)
Location: fs/file_table.c:369
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
c056e7a8-c056e810: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (c00000000047bb40)
Location: fs/file_table.c:369
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
c00000000047bb40-c00000000047bb8c: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffe000258608)
Location: fs/file_table.c:369
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffe000258608-ffffffe00025865a: __fput_sync (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812d7760)
Location: fs/file_table.c:369
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff812d7760-ffffffff812d7789: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812c83e0)
Location: fs/file_table.c:369
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff812c83e0-ffffffff812c8409: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812d5570)
Location: fs/file_table.c:369
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff812d5570-ffffffff812d5599: __fput_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __fput_sync(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812e63c0)
Location: fs/file_table.c:369
Inline: True
Direct callers:
  - kernel/acct.c:close_work
```
**Symbols:**

```
ffffffff812e63c0-ffffffff812e63e9: __fput_sync (STB_GLOBAL)
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
