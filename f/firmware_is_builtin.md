# Function: <code>firmware_is_builtin</code>

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
bool firmware_is_builtin(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/builtin/main.c (ffffffff819a1b40)
Location: drivers/base/firmware_loader/builtin/main.c:95
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff819a1b40-ffffffff819a1b8b: firmware_is_builtin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool firmware_is_builtin(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/builtin/main.c (ffffffff81b139d0)
Location: drivers/base/firmware_loader/builtin/main.c:95
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81b139d0-ffffffff81b13a1b: firmware_is_builtin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool firmware_is_builtin(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/builtin/main.c (ffffffff81b62700)
Location: drivers/base/firmware_loader/builtin/main.c:95
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81b62700-ffffffff81b6274b: firmware_is_builtin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool firmware_is_builtin(const struct firmware *fw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/builtin/main.c (ffffffff81bb6210)
Location: drivers/base/firmware_loader/builtin/main.c:95
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81bb6210-ffffffff81bb625b: firmware_is_builtin (STB_GLOBAL)
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
