# Function: <code>xts_encrypt_done</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xts_encrypt_done(struct crypto_async_request *areq, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8154a930)
Location: crypto/xts.c:198
Inline: False
```
**Symbols:**

```
ffffffff8154a930-ffffffff8154a994: xts_encrypt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xts_encrypt_done(struct crypto_async_request *areq, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81552f50)
Location: crypto/xts.c:199
Inline: False
```
**Symbols:**

```
ffffffff81552f50-ffffffff81552fb4: xts_encrypt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xts_encrypt_done(struct crypto_async_request *areq, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff815b3f80)
Location: crypto/xts.c:199
Inline: False
```
**Symbols:**

```
ffffffff815b3f80-ffffffff815b3fe4: xts_encrypt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xts_encrypt_done(struct crypto_async_request *areq, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8165cd90)
Location: crypto/xts.c:199
Inline: False
```
**Symbols:**

```
ffffffff8165cd90-ffffffff8165ce00: xts_encrypt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xts_encrypt_done(struct crypto_async_request *areq, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81716810)
Location: crypto/xts.c:199
Inline: False
```
**Symbols:**

```
ffffffff81716810-ffffffff81716885: xts_encrypt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xts_encrypt_done(void *data, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff817520d0)
Location: crypto/xts.c:199
Inline: False
```
**Symbols:**

```
ffffffff817520d0-ffffffff81752141: xts_encrypt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xts_encrypt_done(void *data, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81793f50)
Location: crypto/xts.c:199
Inline: False
```
**Symbols:**

```
ffffffff81793f50-ffffffff81793fc1: xts_encrypt_done (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *data</code>
</li>
<li>
<b>Param removed. </b>
<code>struct crypto_async_request *areq</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
