# Function: <code>firmware_request_platform</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int firmware_request_platform(const struct firmware **firmware, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d60d0)
Location: drivers/base/firmware_loader/main.c:902
Inline: False
```
**Symbols:**

```
ffffffff817d60d0-ffffffff817d611d: firmware_request_platform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int firmware_request_platform(const struct firmware **firmware, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817eab10)
Location: drivers/base/firmware_loader/main.c:944
Inline: False
```
**Symbols:**

```
ffffffff817eab10-ffffffff817eab60: firmware_request_platform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int firmware_request_platform(const struct firmware **firmware, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817cf2a0)
Location: drivers/base/firmware_loader/main.c:948
Inline: False
```
**Symbols:**

```
ffffffff817cf2a0-ffffffff817cf2f0: firmware_request_platform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int firmware_request_platform(const struct firmware **firmware, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81859ab0)
Location: drivers/base/firmware_loader/main.c:947
Inline: False
```
**Symbols:**

```
ffffffff81859ab0-ffffffff81859b00: firmware_request_platform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int firmware_request_platform(const struct firmware **firmware, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff819a06b0)
Location: drivers/base/firmware_loader/main.c:972
Inline: False
```
**Symbols:**

```
ffffffff819a06b0-ffffffff819a070e: firmware_request_platform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int firmware_request_platform(const struct firmware **firmware, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b12280)
Location: drivers/base/firmware_loader/main.c:972
Inline: False
```
**Symbols:**

```
ffffffff81b12280-ffffffff81b122de: firmware_request_platform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int firmware_request_platform(const struct firmware **firmware, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b60570)
Location: drivers/base/firmware_loader/main.c:1027
Inline: False
```
**Symbols:**

```
ffffffff81b60570-ffffffff81b605ce: firmware_request_platform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int firmware_request_platform(const struct firmware **firmware, const char *name, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb3fb0)
Location: drivers/base/firmware_loader/main.c:1028
Inline: False
```
**Symbols:**

```
ffffffff81bb3fb0-ffffffff81bb400e: firmware_request_platform (STB_GLOBAL)
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
