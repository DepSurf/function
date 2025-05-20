# Function: <code>ext4_release_io_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8129f8b0)
Location: fs/ext4/page-io.c:124
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
```
**Symbols:**

```
ffffffff8129f8b0-ffffffff8129f980: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff812ce170)
Location: fs/ext4/page-io.c:123
Inline: True
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff812ce170-ffffffff812ce1e8: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff812e3f60)
Location: fs/ext4/page-io.c:123
Inline: True
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff812e3f60-ffffffff812e3fd8: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8131db90)
Location: fs/ext4/page-io.c:122
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff8131db90-ffffffff8131dbf9: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813421a0)
Location: fs/ext4/page-io.c:123
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff813421a0-ffffffff81342209: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81370020)
Location: fs/ext4/page-io.c:123
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff81370020-ffffffff81370089: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813884b0)
Location: fs/ext4/page-io.c:123
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff813884b0-ffffffff81388519: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (0)
Location: fs/ext4/page-io.c:115
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff813b2570-ffffffff813b25d9: ext4_release_io_end (STB_LOCAL)
ffffffff813b3104-ffffffff813b3117: ext4_release_io_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813cb5c0)
Location: fs/ext4/page-io.c:115
Inline: True
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff813cb5c0-ffffffff813cb629: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff814176e0)
Location: fs/ext4/page-io.c:151
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
```
**Symbols:**

```
ffffffff814176e0-ffffffff814177ba: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8142b1e0)
Location: fs/ext4/page-io.c:148
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
```
**Symbols:**

```
ffffffff8142b1e0-ffffffff8142b2ba: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81431d50)
Location: fs/ext4/page-io.c:148
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff81431d50-ffffffff81431e2a: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff814855a0)
Location: fs/ext4/page-io.c:148
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff814855a0-ffffffff8148567a: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81508a10)
Location: fs/ext4/page-io.c:150
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff81508a10-ffffffff81508af4: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff815a3530)
Location: fs/ext4/page-io.c:150
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff815a3530-ffffffff815a3614: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff815d9fc0)
Location: fs/ext4/page-io.c:150
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff815d9fc0-ffffffff815da0a4: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff816126a0)
Location: fs/ext4/page-io.c:150
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff816126a0-ffffffff81612784: ext4_release_io_end (STB_LOCAL)
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
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffff8000104a34b8)
Location: fs/ext4/page-io.c:115
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffff8000104a34b8-ffff8000104a3544: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (c06654a8)
Location: fs/ext4/page-io.c:115
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
c06654a8-c0665548: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (c0000000005d04c0)
Location: fs/ext4/page-io.c:115
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
c0000000005d04c0-c0000000005d0580: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffe000324ce8)
Location: fs/ext4/page-io.c:115
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffe000324ce8-ffffffe000324d60: ext4_release_io_end (STB_LOCAL)
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
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813c3ba0)
Location: fs/ext4/page-io.c:115
Inline: True
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff813c3ba0-ffffffff813c3c09: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813b4620)
Location: fs/ext4/page-io.c:115
Inline: True
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff813b4620-ffffffff813b4689: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813c1030)
Location: fs/ext4/page-io.c:115
Inline: True
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff813c1030-ffffffff813c1099: ext4_release_io_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ext4_release_io_end(ext4_io_end_t *io_end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813d6190)
Location: fs/ext4/page-io.c:115
Inline: True
Direct callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
**Symbols:**

```
ffffffff813d6190-ffffffff813d61f9: ext4_release_io_end (STB_LOCAL)
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
