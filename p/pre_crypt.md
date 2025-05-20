# Function: <code>pre_crypt</code>

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
int pre_crypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814018d0)
Location: crypto/xts.c:150
Inline: False
Direct callers:
  - crypto/xts.c:do_decrypt
  - crypto/xts.c:do_encrypt
```
**Symbols:**

```
ffffffff814018d0-ffffffff81401b97: pre_crypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pre_crypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8140eca0)
Location: crypto/xts.c:150
Inline: False
Direct callers:
  - crypto/xts.c:do_decrypt
  - crypto/xts.c:do_encrypt
```
**Symbols:**

```
ffffffff8140eca0-ffffffff8140ef68: pre_crypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pre_crypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81437770)
Location: crypto/xts.c:150
Inline: False
Direct callers:
  - crypto/xts.c:do_decrypt
  - crypto/xts.c:do_encrypt
```
**Symbols:**

```
ffffffff81437770-ffffffff81437a38: pre_crypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pre_crypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8146a0b0)
Location: crypto/xts.c:150
Inline: False
Direct callers:
  - crypto/xts.c:do_decrypt
  - crypto/xts.c:do_encrypt
```
**Symbols:**

```
ffffffff8146a0b0-ffffffff8146a352: pre_crypt (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
