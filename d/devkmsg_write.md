# Function: <code>devkmsg_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d8a00)
Location: kernel/printk/printk.c:615
Inline: False
```
**Symbols:**

```
ffffffff810d8a00-ffffffff810d8b22: devkmsg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dd4b0)
Location: kernel/printk/printk.c:726
Inline: False
```
**Symbols:**

```
ffffffff810dd4b0-ffffffff810dd621: devkmsg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e3ae0)
Location: kernel/printk/printk.c:708
Inline: False
```
**Symbols:**

```
ffffffff810e3ae0-ffffffff810e3c50: devkmsg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e3af0)
Location: kernel/printk/printk.c:757
Inline: False
```
**Symbols:**

```
ffffffff810e3af0-ffffffff810e3c72: devkmsg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ebd90)
Location: kernel/printk/printk.c:756
Inline: False
```
**Symbols:**

```
ffffffff810ebd90-ffffffff810ebf12: devkmsg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:760
Inline: False
```
**Symbols:**

```
ffffffff810f4960-ffffffff810f4a9f: devkmsg_write (STB_LOCAL)
ffffffff810f5058-ffffffff810f50a6: devkmsg_write.cold.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:769
Inline: False
```
**Symbols:**

```
ffffffff81100160-ffffffff8110029f: devkmsg_write (STB_LOCAL)
ffffffff81100818-ffffffff81100861: devkmsg_write.cold.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:795
Inline: False
```
**Symbols:**

```
ffffffff81108930-ffffffff81108a7a: devkmsg_write (STB_LOCAL)
ffffffff81108ffc-ffffffff81109042: devkmsg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:805
Inline: False
```
**Symbols:**

```
ffffffff81114d10-ffffffff81114e57: devkmsg_write (STB_LOCAL)
ffffffff811153de-ffffffff81115424: devkmsg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:817
Inline: False
```
**Symbols:**

```
ffffffff81120360-ffffffff8112049f: devkmsg_write (STB_LOCAL)
ffffffff81120d75-ffffffff81120dbb: devkmsg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:645
Inline: False
```
**Symbols:**

```
ffffffff8111b300-ffffffff8111b43f: devkmsg_write (STB_LOCAL)
ffffffff81be1381-ffffffff81be13c7: devkmsg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:658
Inline: False
```
**Symbols:**

```
ffffffff8111b9e0-ffffffff8111bb1f: devkmsg_write (STB_LOCAL)
ffffffff81bd3402-ffffffff81bd344a: devkmsg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:653
Inline: False
```
**Symbols:**

```
ffffffff8113c0b0-ffffffff8113c20b: devkmsg_write (STB_LOCAL)
ffffffff81cac592-ffffffff81cac5da: devkmsg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:658
Inline: False
```
**Symbols:**

```
ffffffff8115ee60-ffffffff8115efba: devkmsg_write (STB_LOCAL)
ffffffff81e5ca7c-ffffffff81e5cac2: devkmsg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81191e80)
Location: kernel/printk/printk.c:739
Inline: False
```
**Symbols:**

```
ffffffff81191e80-ffffffff81192030: devkmsg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a3720)
Location: kernel/printk/printk.c:725
Inline: False
```
**Symbols:**

```
ffffffff811a3720-ffffffff811a38cd: devkmsg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811b24c0)
Location: kernel/printk/printk.c:722
Inline: False
```
**Symbols:**

```
ffffffff811b24c0-ffffffff811b266d: devkmsg_write (STB_LOCAL)
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
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010175e18)
Location: kernel/printk/printk.c:805
Inline: False
```
**Symbols:**

```
ffff800010175e18-ffff800010175fa0: devkmsg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c8018)
Location: kernel/printk/printk.c:805
Inline: False
```
**Symbols:**

```
c03c8018-c03c81f8: devkmsg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cf810)
Location: kernel/printk/printk.c:805
Inline: False
```
**Symbols:**

```
c0000000001cf810-c0000000001cfa0c: devkmsg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe0001114be)
Location: kernel/printk/printk.c:805
Inline: False
```
**Symbols:**

```
ffffffe0001114be-ffffffe0001115ea: devkmsg_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:805
Inline: False
```
**Symbols:**

```
ffffffff8110d2f0-ffffffff8110d437: devkmsg_write (STB_LOCAL)
ffffffff8110d9be-ffffffff8110da04: devkmsg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:805
Inline: False
```
**Symbols:**

```
ffffffff810fe070-ffffffff810fe1b7: devkmsg_write (STB_LOCAL)
ffffffff810fe71e-ffffffff810fe764: devkmsg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:805
Inline: False
```
**Symbols:**

```
ffffffff8110b1e0-ffffffff8110b327: devkmsg_write (STB_LOCAL)
ffffffff8110b8ae-ffffffff8110b8f4: devkmsg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t devkmsg_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:805
Inline: False
```
**Symbols:**

```
ffffffff811166b0-ffffffff811167f7: devkmsg_write (STB_LOCAL)
ffffffff81116dc4-ffffffff81116e0a: devkmsg_write.cold (STB_LOCAL)
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
