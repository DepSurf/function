# Function: <code>skcipher_next_copy</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff813f6677)
Location: crypto/skcipher.c:279
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81402a93)
Location: crypto/skcipher.c:280
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8142b103)
Location: crypto/skcipher.c:280
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffff8145de67)
Location: crypto/skcipher.c:281
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffff8147b707)
Location: crypto/skcipher.c:281
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffff814a9995)
Location: crypto/skcipher.c:281
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffff814c4685)
Location: crypto/skcipher.c:285
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skcipher_next_copy(struct skcipher_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81523120)
Location: crypto/skcipher.c:285
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
```
**Symbols:**

```
ffffffff81523120-ffffffff8152324c: skcipher_next_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skcipher_next_copy(struct skcipher_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81540070)
Location: crypto/skcipher.c:285
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
```
**Symbols:**

```
ffffffff81540070-ffffffff8154019c: skcipher_next_copy (STB_LOCAL)
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
In crypto/skcipher.c (ffffffff8154896c)
Location: crypto/skcipher.c:286
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffff815a914c)
Location: crypto/skcipher.c:286
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skcipher_next_copy(struct skcipher_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81650350)
Location: crypto/skcipher.c:286
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
```
**Symbols:**

```
ffffffff81650350-ffffffff8165046a: skcipher_next_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skcipher_next_copy(struct skcipher_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81709ae0)
Location: crypto/skcipher.c:286
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
```
**Symbols:**

```
ffffffff81709ae0-ffffffff81709bfa: skcipher_next_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skcipher_next_copy(struct skcipher_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81743330)
Location: crypto/skcipher.c:304
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
```
**Symbols:**

```
ffffffff81743330-ffffffff8174344a: skcipher_next_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skcipher_next_copy(struct skcipher_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81785630)
Location: crypto/skcipher.c:303
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
```
**Symbols:**

```
ffffffff81785630-ffffffff81785779: skcipher_next_copy (STB_LOCAL)
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
In crypto/skcipher.c (ffff8000105bf284)
Location: crypto/skcipher.c:285
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c076caec)
Location: crypto/skcipher.c:285
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (c000000000746b18)
Location: crypto/skcipher.c:285
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffe00040448a)
Location: crypto/skcipher.c:285
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffff814bcc65)
Location: crypto/skcipher.c:285
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffff814ad685)
Location: crypto/skcipher.c:285
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffff814b8cf5)
Location: crypto/skcipher.c:285
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffff814d17b5)
Location: crypto/skcipher.c:285
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
