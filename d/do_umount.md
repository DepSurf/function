# Function: <code>do_umount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_umount(struct mount *mnt, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122d290)
Location: fs/namespace.c:1451
Inline: False
Direct callers:
  - fs/namespace.c:SyS_oldumount
```
**Symbols:**

```
ffffffff8122d290-ffffffff8122d5b6: do_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_umount(struct mount *mnt, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81255a30)
Location: fs/namespace.c:1451
Inline: False
Direct callers:
  - fs/namespace.c:SyS_oldumount
```
**Symbols:**

```
ffffffff81255a30-ffffffff81255d86: do_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_umount(struct mount *mnt, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81268e20)
Location: fs/namespace.c:1530
Inline: False
Direct callers:
  - fs/namespace.c:SyS_oldumount
```
**Symbols:**

```
ffffffff81268e20-ffffffff81269176: do_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_umount(struct mount *mnt, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812765d0)
Location: fs/namespace.c:1472
Inline: False
Direct callers:
  - fs/namespace.c:SyS_oldumount
```
**Symbols:**

```
ffffffff812765d0-ffffffff81276911: do_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_umount(struct mount *mnt, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81298f20)
Location: fs/namespace.c:1537
Inline: False
Direct callers:
  - fs/namespace.c:SyS_oldumount
```
**Symbols:**

```
ffffffff81298f20-ffffffff81299264: do_umount (STB_LOCAL)
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
In fs/namespace.c (ffffffff812bfbd6)
Location: fs/namespace.c:1563
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffff812d4dd6)
Location: fs/namespace.c:1475
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffff812f228c)
Location: fs/namespace.c:1514
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffff81303e49)
Location: fs/namespace.c:1514
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_umount(struct mount *mnt, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133ce60)
Location: fs/namespace.c:1564
Inline: False
Direct callers:
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffff8133ce60-ffffffff8133d116: do_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_umount(struct mount *mnt, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81348d20)
Location: fs/namespace.c:1567
Inline: False
Direct callers:
  - fs/namespace.c:path_umount
```
**Symbols:**

```
ffffffff81348d20-ffffffff81348fd7: do_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_umount(struct mount *mnt, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134f5c0)
Location: fs/namespace.c:1578
Inline: False
Direct callers:
  - fs/namespace.c:path_umount
```
**Symbols:**

```
ffffffff8134f5c0-ffffffff8134f9c5: do_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_umount(struct mount *mnt, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139d8a0)
Location: fs/namespace.c:1587
Inline: False
Direct callers:
  - fs/namespace.c:path_umount
```
**Symbols:**

```
ffffffff8139d8a0-ffffffff8139dcf2: do_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_umount(struct mount *mnt, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81420880)
Location: fs/namespace.c:1628
Inline: False
Direct callers:
  - fs/namespace.c:path_umount
```
**Symbols:**

```
ffffffff81420880-ffffffff81420ccf: do_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_umount(struct mount *mnt, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814acfc0)
Location: fs/namespace.c:1733
Inline: False
Direct callers:
  - fs/namespace.c:path_umount
```
**Symbols:**

```
ffffffff814acfc0-ffffffff814ad391: do_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_umount(struct mount *mnt, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e1d80)
Location: fs/namespace.c:1707
Inline: False
Direct callers:
  - fs/namespace.c:path_umount
```
**Symbols:**

```
ffffffff814e1d80-ffffffff814e2172: do_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_umount(struct mount *mnt, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81515e50)
Location: fs/namespace.c:1707
Inline: False
Direct callers:
  - fs/namespace.c:path_umount
```
**Symbols:**

```
ffffffff81515e50-ffffffff81516255: do_umount (STB_LOCAL)
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
In fs/namespace.c (ffff8000103b756c)
Location: fs/namespace.c:1514
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_umount(struct mount *mnt, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0594bc8)
Location: fs/namespace.c:1514
Inline: False
Direct callers:
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
c0594bc8-c0594fe4: do_umount (STB_LOCAL)
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
In fs/namespace.c (c0000000004b4160)
Location: fs/namespace.c:1514
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffe00027a106)
Location: fs/namespace.c:1514
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffff812fc429)
Location: fs/namespace.c:1514
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffff812ed049)
Location: fs/namespace.c:1514
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffff812fa219)
Location: fs/namespace.c:1514
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
In fs/namespace.c (ffffffff8130b559)
Location: fs/namespace.c:1514
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
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
