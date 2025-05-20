# Function: <code>ablkcipher_walk_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ablkcipher_walk_done(struct ablkcipher_request *req, struct ablkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ablkcipher.c (ffffffff8139fb60)
Location: crypto/ablkcipher.c:108
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
**Symbols:**

```
ffffffff8139fb60-ffffffff8139fd51: ablkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ablkcipher_walk_done(struct ablkcipher_request *req, struct ablkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ablkcipher.c (ffffffff813dcab0)
Location: crypto/ablkcipher.c:105
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
**Symbols:**

```
ffffffff813dcab0-ffffffff813dcc9c: ablkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ablkcipher_walk_done(struct ablkcipher_request *req, struct ablkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ablkcipher.c (ffffffff813f4390)
Location: crypto/ablkcipher.c:105
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
**Symbols:**

```
ffffffff813f4390-ffffffff813f457c: ablkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ablkcipher_walk_done(struct ablkcipher_request *req, struct ablkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ablkcipher.c (ffffffff814006e0)
Location: crypto/ablkcipher.c:106
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
**Symbols:**

```
ffffffff814006e0-ffffffff814008b9: ablkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ablkcipher_walk_done(struct ablkcipher_request *req, struct ablkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ablkcipher.c (ffffffff81428ce0)
Location: crypto/ablkcipher.c:106
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
**Symbols:**

```
ffffffff81428ce0-ffffffff81428eb9: ablkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ablkcipher_walk_done(struct ablkcipher_request *req, struct ablkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ablkcipher.c (ffffffff8145bb10)
Location: crypto/ablkcipher.c:100
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
**Symbols:**

```
ffffffff8145bb10-ffffffff8145bc95: ablkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ablkcipher_walk_done(struct ablkcipher_request *req, struct ablkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ablkcipher.c (ffffffff81479410)
Location: crypto/ablkcipher.c:100
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
**Symbols:**

```
ffffffff81479410-ffffffff81479595: ablkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ablkcipher_walk_done(struct ablkcipher_request *req, struct ablkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/ablkcipher.c (0)
Location: crypto/ablkcipher.c:95
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
**Symbols:**

```
ffffffff814a78da-ffffffff814a78f3: ablkcipher_walk_done.cold (STB_LOCAL)
ffffffff814a74d0-ffffffff814a7665: ablkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ablkcipher_walk_done(struct ablkcipher_request *req, struct ablkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ablkcipher.c (ffffffff814c2140)
Location: crypto/ablkcipher.c:95
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
**Symbols:**

```
ffffffff814c2140-ffffffff814c22e2: ablkcipher_walk_done (STB_GLOBAL)
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
int ablkcipher_walk_done(struct ablkcipher_request *req, struct ablkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ablkcipher.c (ffff8000105bc578)
Location: crypto/ablkcipher.c:95
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
**Symbols:**

```
ffff8000105bc578-ffff8000105bc7a4: ablkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ablkcipher_walk_done(struct ablkcipher_request *req, struct ablkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ablkcipher.c (c076a668)
Location: crypto/ablkcipher.c:95
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
**Symbols:**

```
c076a668-c076a8bc: ablkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ablkcipher_walk_done(struct ablkcipher_request *req, struct ablkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ablkcipher.c (c0000000007434c0)
Location: crypto/ablkcipher.c:95
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
**Symbols:**

```
c0000000007434c0-c000000000743830: ablkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ablkcipher_walk_done(struct ablkcipher_request *req, struct ablkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ablkcipher.c (ffffffe000401e18)
Location: crypto/ablkcipher.c:95
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
**Symbols:**

```
ffffffe000401e18-ffffffe000401fb2: ablkcipher_walk_done (STB_GLOBAL)
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
int ablkcipher_walk_done(struct ablkcipher_request *req, struct ablkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ablkcipher.c (ffffffff814ba720)
Location: crypto/ablkcipher.c:95
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
**Symbols:**

```
ffffffff814ba720-ffffffff814ba8c2: ablkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ablkcipher_walk_done(struct ablkcipher_request *req, struct ablkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ablkcipher.c (ffffffff814ab140)
Location: crypto/ablkcipher.c:95
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
**Symbols:**

```
ffffffff814ab140-ffffffff814ab2e2: ablkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ablkcipher_walk_done(struct ablkcipher_request *req, struct ablkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ablkcipher.c (ffffffff814b67b0)
Location: crypto/ablkcipher.c:95
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
**Symbols:**

```
ffffffff814b67b0-ffffffff814b6952: ablkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ablkcipher_walk_done(struct ablkcipher_request *req, struct ablkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ablkcipher.c (ffffffff814cf250)
Location: crypto/ablkcipher.c:95
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
**Symbols:**

```
ffffffff814cf250-ffffffff814cf3e2: ablkcipher_walk_done (STB_GLOBAL)
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
