# Function: <code>do_encrypt</code>

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
int do_encrypt(struct skcipher_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81401cc0)
Location: crypto/xts.c:257
Inline: False
Direct callers:
  - crypto/xts.c:encrypt
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffff81401cc0-ffffffff81401d57: do_encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_encrypt(struct skcipher_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8140f0a0)
Location: crypto/xts.c:260
Inline: False
Direct callers:
  - crypto/xts.c:encrypt
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffff8140f0a0-ffffffff8140f137: do_encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_encrypt(struct skcipher_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81437b80)
Location: crypto/xts.c:260
Inline: False
Direct callers:
  - crypto/xts.c:encrypt
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffff81437b80-ffffffff81437c2a: do_encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_encrypt(struct skcipher_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8146a4c0)
Location: crypto/xts.c:260
Inline: False
Direct callers:
  - crypto/xts.c:encrypt
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffff8146a4c0-ffffffff8146a588: do_encrypt (STB_LOCAL)
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
