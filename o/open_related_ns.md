# Function: <code>open_related_ns</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8127d7c0)
Location: fs/nsfs.c:121
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff8127d7c0-ffffffff8127d8a9: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8128b330)
Location: fs/nsfs.c:122
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff8128b330-ffffffff8128b430: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff812ade90)
Location: fs/nsfs.c:123
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff812ade90-ffffffff812adf92: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff812d5c20)
Location: fs/nsfs.c:146
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff812d5c20-ffffffff812d5d1d: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff812eaff0)
Location: fs/nsfs.c:146
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff812eaff0-ffffffff812eb0ed: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81309a60)
Location: fs/nsfs.c:145
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81309a60-ffffffff81309b6f: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8131cad0)
Location: fs/nsfs.c:145
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff8131cad0-ffffffff8131cbdf: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81356730)
Location: fs/nsfs.c:147
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81356730-ffffffff81356831: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813630e0)
Location: fs/nsfs.c:147
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff813630e0-ffffffff813631e1: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81369b80)
Location: fs/nsfs.c:147
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81369b80-ffffffff81369c7f: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813b8870)
Location: fs/nsfs.c:147
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff813b8870-ffffffff813b896f: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8143e140)
Location: fs/nsfs.c:147
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff8143e140-ffffffff8143e24d: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff814ccb60)
Location: fs/nsfs.c:147
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff814ccb60-ffffffff814ccc6d: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81502da0)
Location: fs/nsfs.c:148
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81502da0-ffffffff81502ead: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff815379c0)
Location: fs/nsfs.c:145
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff815379c0-ffffffff81537acd: open_related_ns (STB_GLOBAL)
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
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffff8000103d4740)
Location: fs/nsfs.c:145
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffff8000103d4740-ffff8000103d4848: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (c05ae69c)
Location: fs/nsfs.c:145
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
c05ae69c-c05ae7b8: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (c0000000004d7450)
Location: fs/nsfs.c:145
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
c0000000004d7450-c0000000004d75e0: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffe00028ebba)
Location: fs/nsfs.c:145
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffe00028ebba-ffffffe00028ec94: open_related_ns (STB_GLOBAL)
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
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813150b0)
Location: fs/nsfs.c:145
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff813150b0-ffffffff813151bf: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81305ca0)
Location: fs/nsfs.c:145
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81305ca0-ffffffff81305daf: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81312ea0)
Location: fs/nsfs.c:145
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81312ea0-ffffffff81312faf: open_related_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int open_related_ns(struct ns_common *ns, struct ns_common * (*get_ns)(struct ns_common *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813246f0)
Location: fs/nsfs.c:145
Inline: False
Direct callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff813246f0-ffffffff813247ff: open_related_ns (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
