# Function: <code>xfer_secondary_pool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81513480)
Location: drivers/char/random.c:976
Inline: True
Direct callers:
  - drivers/char/random.c:extract_entropy
  - drivers/char/random.c:extract_entropy_user
```
**Symbols:**

```
ffffffff81513480-ffffffff815134de: xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81566f10)
Location: drivers/char/random.c:1216
Inline: True
Direct callers:
  - drivers/char/random.c:extract_entropy
```
**Symbols:**

```
ffffffff81566f10-ffffffff81566f6f: xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81593670)
Location: drivers/char/random.c:1216
Inline: True
Direct callers:
  - drivers/char/random.c:extract_entropy
```
**Symbols:**

```
ffffffff81593670-ffffffff815936cf: xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a7440)
Location: drivers/char/random.c:1209
Inline: False
```
**Symbols:**

```
ffffffff815a7440-ffffffff815a7471: xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160dd50)
Location: drivers/char/random.c:1208
Inline: False
```
**Symbols:**

```
ffffffff8160dd50-ffffffff8160dd81: xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81647840)
Location: drivers/char/random.c:1312
Inline: False
```
**Symbols:**

```
ffffffff81647840-ffffffff81647870: xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81665ce0)
Location: drivers/char/random.c:1321
Inline: False
```
**Symbols:**

```
ffffffff81665ce0-ffffffff81665d10: xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8169b730)
Location: drivers/char/random.c:1398
Inline: False
```
**Symbols:**

```
ffffffff8169b730-ffffffff8169b760: xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816be450)
Location: drivers/char/random.c:1398
Inline: False
```
**Symbols:**

```
ffffffff816be450-ffffffff816be480: xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108af070)
Location: drivers/char/random.c:1398
Inline: False
```
**Symbols:**

```
ffff8000108af070-ffff8000108af0d8: xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c09ab8e8)
Location: drivers/char/random.c:1398
Inline: False
```
**Symbols:**

```
c09ab8e8-c09ab92c: xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000948eb0)
Location: drivers/char/random.c:1398
Inline: False
```
**Symbols:**

```
c000000000948eb0-c000000000948ef0: xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffe000562b60)
Location: drivers/char/random.c:1398
Inline: False
```
**Symbols:**

```
ffffffe000562b60-ffffffe000562bb4: xfer_secondary_pool (STB_LOCAL)
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
void xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81683ec0)
Location: drivers/char/random.c:1398
Inline: False
```
**Symbols:**

```
ffffffff81683ec0-ffffffff81683ef0: xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81661b40)
Location: drivers/char/random.c:1398
Inline: False
```
**Symbols:**

```
ffffffff81661b40-ffffffff81661b70: xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b2290)
Location: drivers/char/random.c:1398
Inline: False
```
**Symbols:**

```
ffffffff816b2290-ffffffff816b22c0: xfer_secondary_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xfer_secondary_pool(struct entropy_store *r, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cc770)
Location: drivers/char/random.c:1398
Inline: False
```
**Symbols:**

```
ffffffff816cc770-ffffffff816cc7a0: xfer_secondary_pool (STB_LOCAL)
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
