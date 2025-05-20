# Function: <code>xts_create</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xts_create(struct crypto_template *tmpl, struct rtattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/xts.c (0)
Location: crypto/xts.c:338
Inline: False
```
**Symbols:**

```
ffffffff8154abf0-ffffffff8154ae92: xts_create (STB_LOCAL)
ffffffff81bf20f7-ffffffff81bf210f: xts_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xts_create(struct crypto_template *tmpl, struct rtattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/xts.c (0)
Location: crypto/xts.c:339
Inline: False
```
**Symbols:**

```
ffffffff81553210-ffffffff815534bd: xts_create (STB_LOCAL)
ffffffff81be40bb-ffffffff81be40d3: xts_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xts_create(struct crypto_template *tmpl, struct rtattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/xts.c (0)
Location: crypto/xts.c:339
Inline: False
```
**Symbols:**

```
ffffffff815b4240-ffffffff815b44ed: xts_create (STB_LOCAL)
ffffffff81cd77da-ffffffff81cd77f2: xts_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xts_create(struct crypto_template *tmpl, struct rtattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/xts.c (0)
Location: crypto/xts.c:339
Inline: False
```
**Symbols:**

```
ffffffff8165d0c0-ffffffff8165d383: xts_create (STB_LOCAL)
ffffffff81e8aa94-ffffffff81e8aaac: xts_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xts_create(struct crypto_template *tmpl, struct rtattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81716bb0)
Location: crypto/xts.c:339
Inline: False
```
**Symbols:**

```
ffffffff81716bb0-ffffffff81716e8b: xts_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xts_create(struct crypto_template *tmpl, struct rtattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81752460)
Location: crypto/xts.c:339
Inline: False
```
**Symbols:**

```
ffffffff81752460-ffffffff81752790: xts_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xts_create(struct crypto_template *tmpl, struct rtattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff817943f0)
Location: crypto/xts.c:340
Inline: False
```
**Symbols:**

```
ffffffff817943f0-ffffffff817947f5: xts_create (STB_LOCAL)
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
