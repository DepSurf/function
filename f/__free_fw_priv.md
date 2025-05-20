# Function: <code>__free_fw_priv</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __free_fw_priv(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8169a330)
Location: drivers/base/firmware_loader/main.c:235
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
**Symbols:**

```
ffffffff8169a330-ffffffff8169a41e: __free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __free_fw_priv(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816bab90)
Location: drivers/base/firmware_loader/main.c:241
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
**Symbols:**

```
ffffffff816bab90-ffffffff816bac7e: __free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __free_fw_priv(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816f5100)
Location: drivers/base/firmware_loader/main.c:242
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
**Symbols:**

```
ffffffff816f5100-ffffffff816f51c0: __free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __free_fw_priv(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81719500)
Location: drivers/base/firmware_loader/main.c:242
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
**Symbols:**

```
ffffffff81719500-ffffffff817195c0: __free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __free_fw_priv(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d52f0)
Location: drivers/base/firmware_loader/main.c:242
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
**Symbols:**

```
ffffffff817d52f0-ffffffff817d53b8: __free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __free_fw_priv(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817e9bc0)
Location: drivers/base/firmware_loader/main.c:263
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
**Symbols:**

```
ffffffff817e9bc0-ffffffff817e9c88: __free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __free_fw_priv(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817ce2f0)
Location: drivers/base/firmware_loader/main.c:264
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
**Symbols:**

```
ffffffff817ce2f0-ffffffff817ce3b8: __free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __free_fw_priv(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:265
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
**Symbols:**

```
ffffffff81858b90-ffffffff81858c64: __free_fw_priv (STB_LOCAL)
ffffffff81d0423f-ffffffff81d04253: __free_fw_priv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __free_fw_priv(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:202
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
**Symbols:**

```
ffffffff8199ebe0-ffffffff8199ecbf: __free_fw_priv (STB_LOCAL)
ffffffff81eccb46-ffffffff81eccb5b: __free_fw_priv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __free_fw_priv(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:202
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
**Symbols:**

```
ffffffff81b105e0-ffffffff81b106bf: __free_fw_priv (STB_LOCAL)
ffffffff82098b29-ffffffff82098b3e: __free_fw_priv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __free_fw_priv(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:202
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
**Symbols:**

```
ffffffff81b5e800-ffffffff81b5e8df: __free_fw_priv (STB_LOCAL)
ffffffff82119ae0-ffffffff82119af5: __free_fw_priv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __free_fw_priv(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:203
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
**Symbols:**

```
ffffffff81bb2170-ffffffff81bb224f: __free_fw_priv (STB_LOCAL)
ffffffff821f79b8-ffffffff821f79cd: __free_fw_priv.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090ca98)
Location: drivers/base/firmware_loader/main.c:242
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f5b00)
Location: drivers/base/firmware_loader/main.c:242
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009ac530)
Location: drivers/base/firmware_loader/main.c:242
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffe000591a32)
Location: drivers/base/firmware_loader/main.c:242
Inline: True
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
void __free_fw_priv(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816df830)
Location: drivers/base/firmware_loader/main.c:242
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
**Symbols:**

```
ffffffff816df830-ffffffff816df8f0: __free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __free_fw_priv(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816b9e70)
Location: drivers/base/firmware_loader/main.c:242
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
**Symbols:**

```
ffffffff816b9e70-ffffffff816b9f30: __free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __free_fw_priv(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8170cf50)
Location: drivers/base/firmware_loader/main.c:242
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
**Symbols:**

```
ffffffff8170cf50-ffffffff8170d010: __free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __free_fw_priv(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817278f0)
Location: drivers/base/firmware_loader/main.c:242
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
**Symbols:**

```
ffffffff817278f0-ffffffff817279b0: __free_fw_priv (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
