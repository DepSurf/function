# Function: <code>errseq_check_and_advance</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8146c680)
Location: lib/errseq.c:176
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff8146c680-ffffffff8146c6a9: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff81498990)
Location: lib/errseq.c:174
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff81498990-ffffffff814989c7: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff814cdc00)
Location: lib/errseq.c:174
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff814cdc00-ffffffff814cdc37: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff814e24d0)
Location: lib/errseq.c:174
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff814e24d0-ffffffff814e2507: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8150e360)
Location: lib/errseq.c:174
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff8150e360-ffffffff8150e384: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8152c280)
Location: lib/errseq.c:174
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff8152c280-ffffffff8152c2a4: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8158fbf0)
Location: lib/errseq.c:174
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/ext4/ext4_jbd2.c:ext4_check_bdev_write_error
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8158fbf0-ffffffff8158fc14: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff815ac760)
Location: lib/errseq.c:175
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/ext4/ext4_jbd2.c:ext4_check_bdev_write_error
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff815ac760-ffffffff815ac784: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff815b73d0)
Location: lib/errseq.c:175
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff815b73d0-ffffffff815b73f4: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8161da00)
Location: lib/errseq.c:175
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8161da00-ffffffff8161da24: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff816eb590)
Location: lib/errseq.c:175
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff816eb590-ffffffff816eb5c0: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff817dbc80)
Location: lib/errseq.c:175
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff817dbc80-ffffffff817dbcb0: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8181b040)
Location: lib/errseq.c:175
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff8181b040-ffffffff8181b070: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff81860380)
Location: lib/errseq.c:175
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
  - fs/ext4/super.c:__ext4_fill_super
  - fs/jbd2/journal.c:journal_init_common
```
**Symbols:**

```
ffffffff81860380-ffffffff818603b0: errseq_check_and_advance (STB_GLOBAL)
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
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffff800010638158)
Location: lib/errseq.c:174
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffff800010638158-ffff8000106381d4: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (c07ddac4)
Location: lib/errseq.c:174
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
c07ddac4-c07ddb2c: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (c0000000007de3d0)
Location: lib/errseq.c:174
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
c0000000007de3d0-c0000000007de428: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffe000464fb0)
Location: lib/errseq.c:174
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffe000464fb0-ffffffe000464ff4: errseq_check_and_advance (STB_GLOBAL)
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
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff81524860)
Location: lib/errseq.c:174
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff81524860-ffffffff81524884: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff81514b40)
Location: lib/errseq.c:174
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff81514b40-ffffffff81514b64: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff815208f0)
Location: lib/errseq.c:174
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff815208f0-ffffffff81520914: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int errseq_check_and_advance(errseq_t *eseq, errseq_t *since);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errseq.c (ffffffff8153a270)
Location: lib/errseq.c:174
Inline: False
Direct callers:
  - mm/filemap.c:file_check_and_advance_wb_err
```
**Symbols:**

```
ffffffff8153a270-ffffffff8153a294: errseq_check_and_advance (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
