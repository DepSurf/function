# Function: <code>skcipher_walk_skcipher</code>

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
int skcipher_walk_skcipher(struct skcipher_walk *walk, struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff813f6a10)
Location: crypto/skcipher.c:449
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
**Symbols:**

```
ffffffff813f6a10-ffffffff813f6ac2: skcipher_walk_skcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int skcipher_walk_skcipher(struct skcipher_walk *walk, struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81402df0)
Location: crypto/skcipher.c:450
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
**Symbols:**

```
ffffffff81402df0-ffffffff81402e9f: skcipher_walk_skcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int skcipher_walk_skcipher(struct skcipher_walk *walk, struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8142b450)
Location: crypto/skcipher.c:445
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
**Symbols:**

```
ffffffff8142b450-ffffffff8142b511: skcipher_walk_skcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skcipher_walk_skcipher(struct skcipher_walk *walk, struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8145e170)
Location: crypto/skcipher.c:446
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
**Symbols:**

```
ffffffff8145e170-ffffffff8145e22d: skcipher_walk_skcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int skcipher_walk_skcipher(struct skcipher_walk *walk, struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8147ba10)
Location: crypto/skcipher.c:444
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
**Symbols:**

```
ffffffff8147ba10-ffffffff8147bacd: skcipher_walk_skcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int skcipher_walk_skcipher(struct skcipher_walk *walk, struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814a9db0)
Location: crypto/skcipher.c:444
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
**Symbols:**

```
ffffffff814a9db0-ffffffff814a9e6d: skcipher_walk_skcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int skcipher_walk_skcipher(struct skcipher_walk *walk, struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814c4aa0)
Location: crypto/skcipher.c:448
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
**Symbols:**

```
ffffffff814c4aa0-ffffffff814c4b5d: skcipher_walk_skcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81523c32)
Location: crypto/skcipher.c:448
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81540b82)
Location: crypto/skcipher.c:448
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815491e2)
Location: crypto/skcipher.c:449
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815a99c2)
Location: crypto/skcipher.c:449
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81650e62)
Location: crypto/skcipher.c:449
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8170a682)
Location: crypto/skcipher.c:449
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81743ed2)
Location: crypto/skcipher.c:467
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skcipher_walk_skcipher(struct skcipher_walk *walk, struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81785ec0)
Location: crypto/skcipher.c:466
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
**Symbols:**

```
ffffffff81785ec0-ffffffff81785fb3: skcipher_walk_skcipher (STB_LOCAL)
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
int skcipher_walk_skcipher(struct skcipher_walk *walk, struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffff8000105bf4e8)
Location: crypto/skcipher.c:448
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
**Symbols:**

```
ffff8000105bf4e8-ffff8000105bf5d4: skcipher_walk_skcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int skcipher_walk_skcipher(struct skcipher_walk *walk, struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c076d240)
Location: crypto/skcipher.c:448
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
**Symbols:**

```
c076d240-c076d318: skcipher_walk_skcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int skcipher_walk_skcipher(struct skcipher_walk *walk, struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c000000000747240)
Location: crypto/skcipher.c:448
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
**Symbols:**

```
c000000000747240-c000000000747328: skcipher_walk_skcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int skcipher_walk_skcipher(struct skcipher_walk *walk, struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffe0004046bc)
Location: crypto/skcipher.c:448
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
**Symbols:**

```
ffffffe0004046bc-ffffffe000404776: skcipher_walk_skcipher (STB_LOCAL)
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
int skcipher_walk_skcipher(struct skcipher_walk *walk, struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814bd080)
Location: crypto/skcipher.c:448
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
**Symbols:**

```
ffffffff814bd080-ffffffff814bd13d: skcipher_walk_skcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int skcipher_walk_skcipher(struct skcipher_walk *walk, struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814adaa0)
Location: crypto/skcipher.c:448
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
**Symbols:**

```
ffffffff814adaa0-ffffffff814adb5d: skcipher_walk_skcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int skcipher_walk_skcipher(struct skcipher_walk *walk, struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814b9110)
Location: crypto/skcipher.c:448
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
**Symbols:**

```
ffffffff814b9110-ffffffff814b91cd: skcipher_walk_skcipher (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int skcipher_walk_skcipher(struct skcipher_walk *walk, struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814d1bd0)
Location: crypto/skcipher.c:448
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
**Symbols:**

```
ffffffff814d1bd0-ffffffff814d1c8d: skcipher_walk_skcipher (STB_LOCAL)
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
