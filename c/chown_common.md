# Function: <code>chown_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int chown_common(struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81209c40)
Location: fs/open.c:571
Inline: False
Direct callers:
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_fchown
```
**Symbols:**

```
ffffffff81209c40-ffffffff81209e1e: chown_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8122fa70)
Location: fs/open.c:571
Inline: False
Direct callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
```
**Symbols:**

```
ffffffff8122fa70-ffffffff8122fc57: chown_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81242010)
Location: fs/open.c:588
Inline: False
Direct callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
```
**Symbols:**

```
ffffffff81242010-ffffffff812421f7: chown_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124d490)
Location: fs/open.c:584
Inline: False
Direct callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
```
**Symbols:**

```
ffffffff8124d490-ffffffff8124d667: chown_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8126f410)
Location: fs/open.c:584
Inline: False
Direct callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
```
**Symbols:**

```
ffffffff8126f410-ffffffff8126f5ea: chown_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81294e60)
Location: fs/open.c:615
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
```
**Symbols:**

```
ffffffff81294e60-ffffffff8129503d: chown_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812a9b50)
Location: fs/open.c:604
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
```
**Symbols:**

```
ffffffff812a9b50-ffffffff812a9d2d: chown_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c62f0)
Location: fs/open.c:624
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
```
**Symbols:**

```
ffffffff812c62f0-ffffffff812c64d2: chown_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d7d00)
Location: fs/open.c:624
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
```
**Symbols:**

```
ffffffff812d7d00-ffffffff812d7ee2: chown_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130dd90)
Location: fs/open.c:653
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
```
**Symbols:**

```
ffffffff8130dd90-ffffffff8130df70: chown_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131b4f0)
Location: fs/open.c:643
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
  - fs/init.c:init_chown
```
**Symbols:**

```
ffffffff8131b4f0-ffffffff8131b6d0: chown_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81321600)
Location: fs/open.c:645
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
  - fs/init.c:init_chown
```
**Symbols:**

```
ffffffff81321600-ffffffff81321816: chown_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136eae0)
Location: fs/open.c:642
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
  - fs/init.c:init_chown
```
**Symbols:**

```
ffffffff8136eae0-ffffffff8136ecf6: chown_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ed310)
Location: fs/open.c:666
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
  - fs/init.c:init_chown
```
**Symbols:**

```
ffffffff813ed310-ffffffff813ed5c4: chown_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81475980)
Location: fs/open.c:702
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
  - fs/init.c:init_chown
```
**Symbols:**

```
ffffffff81475980-ffffffff81475c5a: chown_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814aa320)
Location: fs/open.c:733
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
  - fs/init.c:init_chown
```
**Symbols:**

```
ffffffff814aa320-ffffffff814aa577: chown_common (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814db7c0)
Location: fs/open.c:753
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
  - fs/init.c:init_chown
```
**Symbols:**

```
ffffffff814db7c0-ffffffff814dba17: chown_common (STB_GLOBAL)
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
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037d0c8)
Location: fs/open.c:624
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
```
**Symbols:**

```
ffff80001037d0c8-ffff80001037d294: chown_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0567f7c)
Location: fs/open.c:624
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
```
**Symbols:**

```
c0567f7c-c0568160: chown_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000472650)
Location: fs/open.c:624
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
```
**Symbols:**

```
c000000000472650-c0000000004728c0: chown_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe0002535d8)
Location: fs/open.c:624
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
```
**Symbols:**

```
ffffffe0002535d8-ffffffe000253756: chown_common (STB_LOCAL)
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
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d02e0)
Location: fs/open.c:624
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
```
**Symbols:**

```
ffffffff812d02e0-ffffffff812d04c2: chown_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c0f60)
Location: fs/open.c:624
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
```
**Symbols:**

```
ffffffff812c0f60-ffffffff812c1142: chown_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812ce0f0)
Location: fs/open.c:624
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
```
**Symbols:**

```
ffffffff812ce0f0-ffffffff812ce2d2: chown_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int chown_common(const struct path *path, uid_t user, gid_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812def00)
Location: fs/open.c:624
Inline: False
Direct callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:do_fchownat
```
**Symbols:**

```
ffffffff812def00-ffffffff812df0e2: chown_common (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
</li>
</ul>
</details>
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
