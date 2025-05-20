# Function: <code>dev_coredumpm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, const void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, const void *, size_t), void (*free)(const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (ffffffff8156c880)
Location: drivers/base/devcoredump.c:230
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpv
```
**Symbols:**

```
ffffffff8156c880-ffffffff8156ca7d: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (ffffffff815c1d20)
Location: drivers/base/devcoredump.c:274
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
```
**Symbols:**

```
ffffffff815c1d20-ffffffff815c1f1d: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (ffffffff815f1170)
Location: drivers/base/devcoredump.c:276
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
```
**Symbols:**

```
ffffffff815f1170-ffffffff815f136d: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (ffffffff816052c0)
Location: drivers/base/devcoredump.c:276
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
```
**Symbols:**

```
ffffffff816052c0-ffffffff816054cc: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (ffffffff8166d6c0)
Location: drivers/base/devcoredump.c:276
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
```
**Symbols:**

```
ffffffff8166d6c0-ffffffff8166d8c8: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (ffffffff816a9100)
Location: drivers/base/devcoredump.c:261
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
```
**Symbols:**

```
ffffffff816a9100-ffffffff816a9301: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (ffffffff816c9ce0)
Location: drivers/base/devcoredump.c:261
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
```
**Symbols:**

```
ffffffff816c9ce0-ffffffff816c9eee: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (ffffffff81705290)
Location: drivers/base/devcoredump.c:261
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
```
**Symbols:**

```
ffffffff81705290-ffffffff81705479: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (ffffffff81729520)
Location: drivers/base/devcoredump.c:252
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
```
**Symbols:**

```
ffffffff81729520-ffffffff81729709: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (ffffffff817e5d50)
Location: drivers/base/devcoredump.c:252
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
```
**Symbols:**

```
ffffffff817e5d50-ffffffff817e5f39: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (ffffffff817fa9e0)
Location: drivers/base/devcoredump.c:252
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
**Symbols:**

```
ffffffff817fa9e0-ffffffff817fabc9: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devcoredump.c (0)
Location: drivers/base/devcoredump.c:252
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
**Symbols:**

```
ffffffff81c01b62-ffffffff81c01b76: dev_coredumpm.cold (STB_LOCAL)
ffffffff817df6f0-ffffffff817df8e9: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devcoredump.c (0)
Location: drivers/base/devcoredump.c:248
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
**Symbols:**

```
ffffffff81d056f3-ffffffff81d05722: dev_coredumpm.cold (STB_LOCAL)
ffffffff8186b160-ffffffff8186b3ab: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devcoredump.c (0)
Location: drivers/base/devcoredump.c:248
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
**Symbols:**

```
ffffffff81ece087-ffffffff81ece0b6: dev_coredumpm.cold (STB_LOCAL)
ffffffff819b3eb0-ffffffff819b410c: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devcoredump.c (0)
Location: drivers/base/devcoredump.c:323
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
**Symbols:**

```
ffffffff82099978-ffffffff82099993: dev_coredumpm.cold (STB_LOCAL)
ffffffff81b28d20-ffffffff81b28fd0: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devcoredump.c (0)
Location: drivers/base/devcoredump.c:322
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
**Symbols:**

```
ffffffff8211aa18-ffffffff8211aa33: dev_coredumpm.cold (STB_LOCAL)
ffffffff81b78ed0-ffffffff81b79180: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devcoredump.c (0)
Location: drivers/base/devcoredump.c:322
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
**Symbols:**

```
ffffffff821f889e-ffffffff821f88b9: dev_coredumpm.cold (STB_LOCAL)
ffffffff81bccda0-ffffffff81bcd080: dev_coredumpm (STB_GLOBAL)
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
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (ffff80001091f290)
Location: drivers/base/devcoredump.c:252
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
```
**Symbols:**

```
ffff80001091f290-ffff80001091f488: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (c0a044fc)
Location: drivers/base/devcoredump.c:252
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
```
**Symbols:**

```
c0a044fc-c0a046d8: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (c0000000009c4580)
Location: drivers/base/devcoredump.c:252
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
```
**Symbols:**

```
c0000000009c4580-c0000000009c4848: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (ffffffe00059e28a)
Location: drivers/base/devcoredump.c:252
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
```
**Symbols:**

```
ffffffe00059e28a-ffffffe00059e442: dev_coredumpm (STB_GLOBAL)
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
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (ffffffff816ef300)
Location: drivers/base/devcoredump.c:252
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
```
**Symbols:**

```
ffffffff816ef300-ffffffff816ef4e9: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (ffffffff8171c9e0)
Location: drivers/base/devcoredump.c:252
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
```
**Symbols:**

```
ffffffff8171c9e0-ffffffff8171cbc9: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dev_coredumpm(struct device *dev, struct module *owner, void *data, size_t datalen, gfp_t gfp, ssize_t (*read)(char *, loff_t, size_t, void *, size_t), void (*free)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devcoredump.c (ffffffff81737d40)
Location: drivers/base/devcoredump.c:252
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:dev_coredumpsg
  - drivers/base/devcoredump.c:dev_coredumpv
```
**Symbols:**

```
ffffffff81737d40-ffffffff81737f29: dev_coredumpm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const void *data</code> ➡️ <code>void *data</code>
</li>
<li>
<b>Param type changed. </b>
<code>ssize_t (*read)(char *, loff_t, size_t, const void *, size_t)</code> ➡️ <code>ssize_t (*read)(char *, loff_t, size_t, void *, size_t)</code>
</li>
<li>
<b>Param type changed. </b>
<code>void (*free)(const void *)</code> ➡️ <code>void (*free)(void *)</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
