# Function: <code>safe_delay_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81697b50)
Location: drivers/md/md.c:3376
Inline: False
```
**Symbols:**

```
ffffffff81697b50-ffffffff81697c59: safe_delay_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f8640)
Location: drivers/md/md.c:3382
Inline: False
```
**Symbols:**

```
ffffffff816f8640-ffffffff816f8747: safe_delay_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81729e60)
Location: drivers/md/md.c:3417
Inline: False
```
**Symbols:**

```
ffffffff81729e60-ffffffff81729f67: safe_delay_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817426b0)
Location: drivers/md/md.c:3553
Inline: False
```
**Symbols:**

```
ffffffff817426b0-ffffffff817427c1: safe_delay_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817b47c0)
Location: drivers/md/md.c:3608
Inline: False
```
**Symbols:**

```
ffffffff817b47c0-ffffffff817b48d1: safe_delay_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817fb880)
Location: drivers/md/md.c:3624
Inline: True
```
**Symbols:**

```
ffffffff817fb880-ffffffff817fb98a: safe_delay_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81827970)
Location: drivers/md/md.c:3615
Inline: True
```
**Symbols:**

```
ffffffff81827970-ffffffff81827a7a: safe_delay_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3682
Inline: False
```
**Symbols:**

```
ffffffff81869e20-ffffffff81869f18: safe_delay_store (STB_LOCAL)
ffffffff8186f358-ffffffff8186f370: safe_delay_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3740
Inline: False
```
**Symbols:**

```
ffffffff8189bbc0-ffffffff8189bcb8: safe_delay_store (STB_LOCAL)
ffffffff818a111b-ffffffff818a1133: safe_delay_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3865
Inline: False
```
**Symbols:**

```
ffffffff8196bbf0-ffffffff8196bce8: safe_delay_store (STB_LOCAL)
ffffffff81970f16-ffffffff81970f2e: safe_delay_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3886
Inline: False
```
**Symbols:**

```
ffffffff819728b0-ffffffff819729a8: safe_delay_store (STB_LOCAL)
ffffffff81c26ffc-ffffffff81c27014: safe_delay_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3850
Inline: False
```
**Symbols:**

```
ffffffff819569a0-ffffffff81956aa4: safe_delay_store (STB_LOCAL)
ffffffff81c191ad-ffffffff81c191c5: safe_delay_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3869
Inline: False
```
**Symbols:**

```
ffffffff819fc040-ffffffff819fc144: safe_delay_store (STB_LOCAL)
ffffffff81d287d3-ffffffff81d287eb: safe_delay_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3859
Inline: False
```
**Symbols:**

```
ffffffff81b636b0-ffffffff81b637c5: safe_delay_store (STB_LOCAL)
ffffffff81ef483f-ffffffff81ef4850: safe_delay_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cfdd40)
Location: drivers/md/md.c:3821
Inline: False
```
**Symbols:**

```
ffffffff81cfdd40-ffffffff81cfde4a: safe_delay_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d64ea0)
Location: drivers/md/md.c:3807
Inline: False
```
**Symbols:**

```
ffffffff81d64ea0-ffffffff81d64fb3: safe_delay_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e1bc30)
Location: drivers/md/md.c:3935
Inline: False
```
**Symbols:**

```
ffffffff81e1bc30-ffffffff81e1bd2c: safe_delay_store (STB_LOCAL)
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
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010af01f8)
Location: drivers/md/md.c:3740
Inline: False
```
**Symbols:**

```
ffff800010af01f8-ffff800010af0328: safe_delay_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bd15fc)
Location: drivers/md/md.c:3740
Inline: False
```
**Symbols:**

```
c0bd15fc-c0bd1714: safe_delay_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bdbf50)
Location: drivers/md/md.c:3740
Inline: False
```
**Symbols:**

```
c000000000bdbf50-c000000000bdc0a4: safe_delay_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006e4320)
Location: drivers/md/md.c:3740
Inline: False
```
**Symbols:**

```
ffffffe0006e4320-ffffffe0006e43de: safe_delay_store (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3740
Inline: False
```
**Symbols:**

```
ffffffff81841a40-ffffffff81841b38: safe_delay_store (STB_LOCAL)
ffffffff81846f9b-ffffffff81846fb3: safe_delay_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3740
Inline: False
```
**Symbols:**

```
ffffffff818090a0-ffffffff81809198: safe_delay_store (STB_LOCAL)
ffffffff8180e5fb-ffffffff8180e613: safe_delay_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3740
Inline: False
```
**Symbols:**

```
ffffffff81891070-ffffffff81891168: safe_delay_store (STB_LOCAL)
ffffffff818965cb-ffffffff818965e3: safe_delay_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t safe_delay_store(struct mddev *mddev, const char *cbuf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3740
Inline: False
```
**Symbols:**

```
ffffffff818acc50-ffffffff818acd48: safe_delay_store (STB_LOCAL)
ffffffff818b25ab-ffffffff818b25c3: safe_delay_store.cold (STB_LOCAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
