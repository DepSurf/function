# Function: <code>firmware_request_builtin_buf</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool firmware_request_builtin_buf(struct firmware *fw, const char *name, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/builtin/main.c (ffffffff819a1a90)
Location: drivers/base/firmware_loader/builtin/main.c:86
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff819a1a90-ffffffff819a1b38: firmware_request_builtin_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool firmware_request_builtin_buf(struct firmware *fw, const char *name, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/builtin/main.c (ffffffff81b13900)
Location: drivers/base/firmware_loader/builtin/main.c:86
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81b13900-ffffffff81b139b8: firmware_request_builtin_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool firmware_request_builtin_buf(struct firmware *fw, const char *name, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/builtin/main.c (ffffffff81b62630)
Location: drivers/base/firmware_loader/builtin/main.c:86
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81b62630-ffffffff81b626e8: firmware_request_builtin_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool firmware_request_builtin_buf(struct firmware *fw, const char *name, void *buf, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/builtin/main.c (ffffffff81bb6140)
Location: drivers/base/firmware_loader/builtin/main.c:86
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81bb6140-ffffffff81bb61f8: firmware_request_builtin_buf (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
