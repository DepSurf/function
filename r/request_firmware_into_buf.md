# Function: <code>request_firmware_into_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815b4620)
Location: drivers/base/firmware_class.c:1275
Inline: False
```
**Symbols:**

```
ffffffff815b4620-ffffffff815b467e: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815e38c0)
Location: drivers/base/firmware_class.c:1310
Inline: False
```
**Symbols:**

```
ffffffff815e38c0-ffffffff815e391e: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815f85a0)
Location: drivers/base/firmware_class.c:1310
Inline: False
```
**Symbols:**

```
ffffffff815f85a0-ffffffff815f85fe: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff816605a0)
Location: drivers/base/firmware_class.c:1317
Inline: False
```
**Symbols:**

```
ffffffff816605a0-ffffffff816605fe: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8169af80)
Location: drivers/base/firmware_loader/main.c:726
Inline: True
```
**Symbols:**

```
ffffffff8169af80-ffffffff8169b007: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816bb800)
Location: drivers/base/firmware_loader/main.c:735
Inline: True
```
**Symbols:**

```
ffffffff816bb800-ffffffff816bb887: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816f5ef0)
Location: drivers/base/firmware_loader/main.c:925
Inline: True
```
**Symbols:**

```
ffffffff816f5ef0-ffffffff816f5f78: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8171a2f0)
Location: drivers/base/firmware_loader/main.c:925
Inline: True
```
**Symbols:**

```
ffffffff8171a2f0-ffffffff8171a378: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d6120)
Location: drivers/base/firmware_loader/main.c:956
Inline: False
```
**Symbols:**

```
ffffffff817d6120-ffffffff817d61a8: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817eab60)
Location: drivers/base/firmware_loader/main.c:998
Inline: False
```
**Symbols:**

```
ffffffff817eab60-ffffffff817eabe8: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817cf2f0)
Location: drivers/base/firmware_loader/main.c:1002
Inline: False
```
**Symbols:**

```
ffffffff817cf2f0-ffffffff817cf378: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81859b00)
Location: drivers/base/firmware_loader/main.c:1001
Inline: False
```
**Symbols:**

```
ffffffff81859b00-ffffffff81859b88: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff819a0710)
Location: drivers/base/firmware_loader/main.c:1026
Inline: False
```
**Symbols:**

```
ffffffff819a0710-ffffffff819a07aa: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b122f0)
Location: drivers/base/firmware_loader/main.c:1026
Inline: False
```
**Symbols:**

```
ffffffff81b122f0-ffffffff81b1238a: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b605e0)
Location: drivers/base/firmware_loader/main.c:1081
Inline: False
```
**Symbols:**

```
ffffffff81b605e0-ffffffff81b6067a: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb4020)
Location: drivers/base/firmware_loader/main.c:1082
Inline: False
```
**Symbols:**

```
ffffffff81bb4020-ffffffff81bb40ba: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090db60)
Location: drivers/base/firmware_loader/main.c:925
Inline: True
```
**Symbols:**

```
ffff80001090db60-ffff80001090dc10: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f6b30)
Location: drivers/base/firmware_loader/main.c:925
Inline: True
```
**Symbols:**

```
c09f6b30-c09f6bc4: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009ae220)
Location: drivers/base/firmware_loader/main.c:925
Inline: True
```
**Symbols:**

```
c0000000009ae220-c0000000009ae31c: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffe00059243c)
Location: drivers/base/firmware_loader/main.c:925
Inline: False
```
**Symbols:**

```
ffffffe00059243c-ffffffe0005924a0: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816e0620)
Location: drivers/base/firmware_loader/main.c:925
Inline: True
```
**Symbols:**

```
ffffffff816e0620-ffffffff816e06a8: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816bac60)
Location: drivers/base/firmware_loader/main.c:925
Inline: True
```
**Symbols:**

```
ffffffff816bac60-ffffffff816bace8: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8170dd30)
Location: drivers/base/firmware_loader/main.c:925
Inline: True
```
**Symbols:**

```
ffffffff8170dd30-ffffffff8170ddb8: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int request_firmware_into_buf(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81728960)
Location: drivers/base/firmware_loader/main.c:925
Inline: True
```
**Symbols:**

```
ffffffff81728960-ffffffff817289e8: request_firmware_into_buf (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
