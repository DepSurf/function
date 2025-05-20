# Function: <code>umh_pipe_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8126eab0)
Location: fs/coredump.c:488
Inline: False
```
**Symbols:**

```
ffffffff8126eab0-ffffffff8126eb43: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8129a220)
Location: fs/coredump.c:515
Inline: False
```
**Symbols:**

```
ffffffff8129a220-ffffffff8129a2b5: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff812aedb0)
Location: fs/coredump.c:518
Inline: False
```
**Symbols:**

```
ffffffff812aedb0-ffffffff812aee45: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff812bc1e0)
Location: fs/coredump.c:520
Inline: False
```
**Symbols:**

```
ffffffff812bc1e0-ffffffff812bc275: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff812dfae0)
Location: fs/coredump.c:521
Inline: False
```
**Symbols:**

```
ffffffff812dfae0-ffffffff812dfb75: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a9160)
Location: kernel/umh.c:422
Inline: False
```
```
In fs/coredump.c (ffffffff8130bd00)
Location: fs/coredump.c:521
Inline: False
```
**Symbols:**

```
ffffffff810a9160-ffffffff810a926b: umh_pipe_setup (STB_LOCAL)
ffffffff8130bd00-ffffffff8130bd95: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b2050)
Location: kernel/umh.c:434
Inline: False
```
```
In fs/coredump.c (ffffffff81321560)
Location: fs/coredump.c:521
Inline: False
```
**Symbols:**

```
ffffffff810b2050-ffffffff810b215c: umh_pipe_setup (STB_LOCAL)
ffffffff81321560-ffffffff813215f5: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b7be0)
Location: kernel/umh.c:435
Inline: False
```
```
In fs/coredump.c (ffffffff81348e10)
Location: fs/coredump.c:547
Inline: False
```
**Symbols:**

```
ffffffff810b7be0-ffffffff810b7cef: umh_pipe_setup (STB_LOCAL)
ffffffff81348e10-ffffffff81348eac: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810be0e0)
Location: kernel/umh.c:435
Inline: False
```
```
In fs/coredump.c (ffffffff813610b0)
Location: fs/coredump.c:547
Inline: False
```
**Symbols:**

```
ffffffff810be0e0-ffffffff810be1ef: umh_pipe_setup (STB_LOCAL)
ffffffff813610b0-ffffffff8136114c: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810c5240)
Location: kernel/umh.c:435
Inline: False
```
```
In fs/coredump.c (ffffffff813a6ec0)
Location: fs/coredump.c:549
Inline: False
```
**Symbols:**

```
ffffffff810c5240-ffffffff810c534f: umh_pipe_setup (STB_LOCAL)
ffffffff813a6ec0-ffffffff813a6f5c: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813b7c80)
Location: fs/coredump.c:559
Inline: False
```
**Symbols:**

```
ffffffff813b7c80-ffffffff813b7d1c: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813bed80)
Location: fs/coredump.c:559
Inline: False
```
**Symbols:**

```
ffffffff813bed80-ffffffff813bee1c: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8140ebb0)
Location: fs/coredump.c:559
Inline: False
```
**Symbols:**

```
ffffffff8140ebb0-ffffffff8140ec4c: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81484360)
Location: fs/coredump.c:493
Inline: False
```
**Symbols:**

```
ffffffff81484360-ffffffff81484414: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81517840)
Location: fs/coredump.c:499
Inline: False
```
**Symbols:**

```
ffffffff81517840-ffffffff815178f4: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8154f110)
Location: fs/coredump.c:501
Inline: False
```
**Symbols:**

```
ffffffff8154f110-ffffffff8154f1c4: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81584f50)
Location: fs/coredump.c:501
Inline: False
```
**Symbols:**

```
ffffffff81584f50-ffffffff81585004: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffff80001011a928)
Location: kernel/umh.c:435
Inline: False
```
```
In fs/coredump.c (ffff800010427650)
Location: fs/coredump.c:547
Inline: False
```
**Symbols:**

```
ffff80001011a928-ffff80001011aa48: umh_pipe_setup (STB_LOCAL)
ffff800010427650-ffff8000104276f0: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (c036ee98)
Location: kernel/umh.c:435
Inline: False
```
```
In fs/coredump.c (c05f0100)
Location: fs/coredump.c:547
Inline: False
```
**Symbols:**

```
c036ee98-c036efc4: umh_pipe_setup (STB_LOCAL)
c05f0100-c05f01b8: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (c000000000162300)
Location: kernel/umh.c:435
Inline: False
```
```
In fs/coredump.c (c000000000537300)
Location: fs/coredump.c:547
Inline: False
```
**Symbols:**

```
c000000000162300-c000000000162494: umh_pipe_setup (STB_LOCAL)
c000000000537300-c0000000005373d0: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffe0000d5082)
Location: kernel/umh.c:435
Inline: False
```
```
In fs/coredump.c (ffffffe0002c5b9e)
Location: fs/coredump.c:547
Inline: False
```
**Symbols:**

```
ffffffe0000d5082-ffffffe0000d51a6: umh_pipe_setup (STB_LOCAL)
ffffffe0002c5b9e-ffffffe0002c5c0c: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b8450)
Location: kernel/umh.c:435
Inline: False
```
```
In fs/coredump.c (ffffffff81359690)
Location: fs/coredump.c:547
Inline: False
```
**Symbols:**

```
ffffffff810b8450-ffffffff810b855f: umh_pipe_setup (STB_LOCAL)
ffffffff81359690-ffffffff8135972c: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810a6d90)
Location: kernel/umh.c:435
Inline: False
```
```
In fs/coredump.c (ffffffff8134a340)
Location: fs/coredump.c:547
Inline: False
```
**Symbols:**

```
ffffffff810a6d90-ffffffff810a6e9f: umh_pipe_setup (STB_LOCAL)
ffffffff8134a340-ffffffff8134a3dc: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810b79b0)
Location: kernel/umh.c:435
Inline: False
```
```
In fs/coredump.c (ffffffff81357160)
Location: fs/coredump.c:547
Inline: False
```
**Symbols:**

```
ffffffff810b79b0-ffffffff810b7abf: umh_pipe_setup (STB_LOCAL)
ffffffff81357160-ffffffff813571fc: umh_pipe_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
int umh_pipe_setup(struct subprocess_info *info, struct cred *new);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/umh.c (ffffffff810bfd20)
Location: kernel/umh.c:435
Inline: False
```
```
In fs/coredump.c (ffffffff8136a840)
Location: fs/coredump.c:547
Inline: False
```
**Symbols:**

```
ffffffff810bfd20-ffffffff810bfe2f: umh_pipe_setup (STB_LOCAL)
ffffffff8136a840-ffffffff8136a8dc: umh_pipe_setup (STB_LOCAL)
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
