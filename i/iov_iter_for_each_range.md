# Function: <code>iov_iter_for_each_range</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iov_iter_for_each_range(struct iov_iter *i, size_t bytes, int (*f)(struct kvec *, void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81491800)
Location: lib/iov_iter.c:1450
Inline: False
```
**Symbols:**

```
ffffffff81491800-ffffffff81491a54: iov_iter_for_each_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iov_iter_for_each_range(struct iov_iter *i, size_t bytes, int (*f)(struct kvec *, void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c67d0)
Location: lib/iov_iter.c:1580
Inline: False
```
**Symbols:**

```
ffffffff814c67d0-ffffffff814c69ee: iov_iter_for_each_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iov_iter_for_each_range(struct iov_iter *i, size_t bytes, int (*f)(struct kvec *, void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814daf60)
Location: lib/iov_iter.c:1676
Inline: False
```
**Symbols:**

```
ffffffff814daf60-ffffffff814db1c9: iov_iter_for_each_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iov_iter_for_each_range(struct iov_iter *i, size_t bytes, int (*f)(struct kvec *, void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81506820)
Location: lib/iov_iter.c:1698
Inline: False
```
**Symbols:**

```
ffffffff81506820-ffffffff81506a97: iov_iter_for_each_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iov_iter_for_each_range(struct iov_iter *i, size_t bytes, int (*f)(struct kvec *, void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81524930)
Location: lib/iov_iter.c:1698
Inline: False
```
**Symbols:**

```
ffffffff81524930-ffffffff81524ba7: iov_iter_for_each_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iov_iter_for_each_range(struct iov_iter *i, size_t bytes, int (*f)(struct kvec *, void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81589140)
Location: lib/iov_iter.c:1734
Inline: False
```
**Symbols:**

```
ffffffff81589140-ffffffff815893ad: iov_iter_for_each_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iov_iter_for_each_range(struct iov_iter *i, size_t bytes, int (*f)(struct kvec *, void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a57d0)
Location: lib/iov_iter.c:1833
Inline: False
```
**Symbols:**

```
ffffffff815a57d0-ffffffff815a59fa: iov_iter_for_each_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iov_iter_for_each_range(struct iov_iter *i, size_t bytes, int (*f)(struct kvec *, void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815ac8c0)
Location: lib/iov_iter.c:2121
Inline: False
```
**Symbols:**

```
ffffffff815ac8c0-ffffffff815acd53: iov_iter_for_each_range (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int iov_iter_for_each_range(struct iov_iter *i, size_t bytes, int (*f)(struct kvec *, void *), void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062e8b8)
Location: lib/iov_iter.c:1698
Inline: True
```
**Symbols:**

```
ffff80001062e8b8-ffff80001062eb5c: iov_iter_for_each_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int iov_iter_for_each_range(struct iov_iter *i, size_t bytes, int (*f)(struct kvec *, void *), void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d51c8)
Location: lib/iov_iter.c:1698
Inline: True
```
**Symbols:**

```
c07d51c8-c07d5460: iov_iter_for_each_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int iov_iter_for_each_range(struct iov_iter *i, size_t bytes, int (*f)(struct kvec *, void *), void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d1ec0)
Location: lib/iov_iter.c:1698
Inline: True
```
**Symbols:**

```
c0000000007d1ec0-c0000000007d22dc: iov_iter_for_each_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int iov_iter_for_each_range(struct iov_iter *i, size_t bytes, int (*f)(struct kvec *, void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045e2ee)
Location: lib/iov_iter.c:1698
Inline: False
```
**Symbols:**

```
ffffffe00045e2ee-ffffffe00045e52a: iov_iter_for_each_range (STB_GLOBAL)
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
int iov_iter_for_each_range(struct iov_iter *i, size_t bytes, int (*f)(struct kvec *, void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151cf10)
Location: lib/iov_iter.c:1698
Inline: False
```
**Symbols:**

```
ffffffff8151cf10-ffffffff8151d187: iov_iter_for_each_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iov_iter_for_each_range(struct iov_iter *i, size_t bytes, int (*f)(struct kvec *, void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150d200)
Location: lib/iov_iter.c:1698
Inline: False
```
**Symbols:**

```
ffffffff8150d200-ffffffff8150d477: iov_iter_for_each_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iov_iter_for_each_range(struct iov_iter *i, size_t bytes, int (*f)(struct kvec *, void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81518fa0)
Location: lib/iov_iter.c:1698
Inline: False
```
**Symbols:**

```
ffffffff81518fa0-ffffffff81519217: iov_iter_for_each_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iov_iter_for_each_range(struct iov_iter *i, size_t bytes, int (*f)(struct kvec *, void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81532790)
Location: lib/iov_iter.c:1698
Inline: False
```
**Symbols:**

```
ffffffff81532790-ffffffff81532a04: iov_iter_for_each_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
