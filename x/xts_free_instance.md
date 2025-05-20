# Function: <code>xts_free_instance</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xts_free_instance(struct skcipher_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8154accc)
Location: crypto/xts.c:330
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
**Symbols:**

```
ffffffff8154ab00-ffffffff8154ab28: xts_free_instance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xts_free_instance(struct skcipher_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff815532f5)
Location: crypto/xts.c:331
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
**Symbols:**

```
ffffffff81553120-ffffffff81553148: xts_free_instance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xts_free_instance(struct skcipher_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff815b4325)
Location: crypto/xts.c:331
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
**Symbols:**

```
ffffffff815b4150-ffffffff815b4178: xts_free_instance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xts_free_instance(struct skcipher_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8165d1b9)
Location: crypto/xts.c:331
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
**Symbols:**

```
ffffffff8165cfb0-ffffffff8165cfdd: xts_free_instance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xts_free_instance(struct skcipher_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81716ca9)
Location: crypto/xts.c:331
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
**Symbols:**

```
ffffffff81716a80-ffffffff81716aad: xts_free_instance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xts_free_instance(struct skcipher_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81752557)
Location: crypto/xts.c:331
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
**Symbols:**

```
ffffffff81752330-ffffffff8175235d: xts_free_instance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xts_free_instance(struct skcipher_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8179454a)
Location: crypto/xts.c:331
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
**Symbols:**

```
ffffffff817941b0-ffffffff817941e9: xts_free_instance (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
