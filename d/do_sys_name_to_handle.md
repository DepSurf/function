# Function: <code>do_sys_name_to_handle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff812700d8)
Location: fs/fhandle.c:15
Inline: True
Inline callers:
  - fs/fhandle.c:SyS_name_to_handle_at
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff8129b8fc)
Location: fs/fhandle.c:15
Inline: True
Inline callers:
  - fs/fhandle.c:SyS_name_to_handle_at
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff812b04bc)
Location: fs/fhandle.c:15
Inline: True
Inline callers:
  - fs/fhandle.c:SyS_name_to_handle_at
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff812bd94c)
Location: fs/fhandle.c:16
Inline: True
Inline callers:
  - fs/fhandle.c:SyS_name_to_handle_at
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff812e150c)
Location: fs/fhandle.c:17
Inline: True
Inline callers:
  - fs/fhandle.c:SyS_name_to_handle_at
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fhandle.c (ffffffff8130d730)
Location: fs/fhandle.c:17
Inline: True
Direct callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
**Symbols:**

```
ffffffff8130d730-ffffffff8130d8b8: do_sys_name_to_handle.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fhandle.c (ffffffff81322c90)
Location: fs/fhandle.c:17
Inline: True
Direct callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
**Symbols:**

```
ffffffff81322c90-ffffffff81322e18: do_sys_name_to_handle.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fhandle.c (ffffffff8134a6b0)
Location: fs/fhandle.c:17
Inline: True
Direct callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
**Symbols:**

```
ffffffff8134a6b0-ffffffff8134a837: do_sys_name_to_handle.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fhandle.c (ffffffff81362950)
Location: fs/fhandle.c:17
Inline: True
Direct callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
**Symbols:**

```
ffffffff81362950-ffffffff81362aeb: do_sys_name_to_handle.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_sys_name_to_handle(struct path *path, struct file_handle *ufh, int *mnt_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff813a8b10)
Location: fs/fhandle.c:17
Inline: False
Direct callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
**Symbols:**

```
ffffffff813a8b10-ffffffff813a8ca3: do_sys_name_to_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_sys_name_to_handle(struct path *path, struct file_handle *ufh, int *mnt_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff813b9e70)
Location: fs/fhandle.c:17
Inline: False
Direct callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
**Symbols:**

```
ffffffff813b9e70-ffffffff813ba003: do_sys_name_to_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_sys_name_to_handle(struct path *path, struct file_handle *ufh, int *mnt_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff813c0fd0)
Location: fs/fhandle.c:17
Inline: False
Direct callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
**Symbols:**

```
ffffffff813c0fd0-ffffffff813c1163: do_sys_name_to_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_sys_name_to_handle(struct path *path, struct file_handle *ufh, int *mnt_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff81410a40)
Location: fs/fhandle.c:17
Inline: False
Direct callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
**Symbols:**

```
ffffffff81410a40-ffffffff81410bd3: do_sys_name_to_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_sys_name_to_handle(struct path *path, struct file_handle *ufh, int *mnt_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff814863c0)
Location: fs/fhandle.c:17
Inline: False
Direct callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
**Symbols:**

```
ffffffff814863c0-ffffffff81486570: do_sys_name_to_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_sys_name_to_handle(const struct path *path, struct file_handle *ufh, int *mnt_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff81519ce0)
Location: fs/fhandle.c:17
Inline: False
Direct callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
**Symbols:**

```
ffffffff81519ce0-ffffffff81519e91: do_sys_name_to_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_sys_name_to_handle(const struct path *path, struct file_handle *ufh, int *mnt_id, int fh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff815515f0)
Location: fs/fhandle.c:17
Inline: False
Direct callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
**Symbols:**

```
ffffffff815515f0-ffffffff815517cd: do_sys_name_to_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_sys_name_to_handle(const struct path *path, struct file_handle *ufh, int *mnt_id, int fh_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff815874f0)
Location: fs/fhandle.c:17
Inline: False
Direct callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
**Symbols:**

```
ffffffff815874f0-ffffffff81587704: do_sys_name_to_handle (STB_LOCAL)
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
In fs/fhandle.c (ffff80001042983c)
Location: fs/fhandle.c:17
Inline: True
Inline callers:
  - fs/fhandle.c:__arm64_sys_name_to_handle_at
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_sys_name_to_handle(struct path *path, struct file_handle *ufh, int *mnt_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (c05f1dd4)
Location: fs/fhandle.c:17
Inline: False
Direct callers:
  - fs/fhandle.c:__se_sys_name_to_handle_at
```
**Symbols:**

```
c05f1dd4-c05f205c: do_sys_name_to_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (c0000000005396c0)
Location: fs/fhandle.c:17
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_name_to_handle_at
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
In fs/fhandle.c (ffffffe0002c7302)
Location: fs/fhandle.c:17
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_name_to_handle_at
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fhandle.c (ffffffff8135af30)
Location: fs/fhandle.c:17
Inline: True
Direct callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
**Symbols:**

```
ffffffff8135af30-ffffffff8135b0cb: do_sys_name_to_handle.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fhandle.c (ffffffff8134bbd0)
Location: fs/fhandle.c:17
Inline: True
Direct callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
**Symbols:**

```
ffffffff8134bbd0-ffffffff8134bd6b: do_sys_name_to_handle.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fhandle.c (ffffffff81358a00)
Location: fs/fhandle.c:17
Inline: True
Direct callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
**Symbols:**

```
ffffffff81358a00-ffffffff81358b9b: do_sys_name_to_handle.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fhandle.c (ffffffff8136c100)
Location: fs/fhandle.c:17
Inline: True
Direct callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
**Symbols:**

```
ffffffff8136c100-ffffffff8136c29b: do_sys_name_to_handle.isra.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int fh_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
