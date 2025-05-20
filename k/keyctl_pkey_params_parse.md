# Function: <code>keyctl_pkey_params_parse</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff814077ba)
Location: security/keys/keyctl_pkey.c:42
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff81434978)
Location: security/keys/keyctl_pkey.c:38
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff8144e6f8)
Location: security/keys/keyctl_pkey.c:38
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int keyctl_pkey_params_parse(struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff814a06c0)
Location: security/keys/keyctl_pkey.c:38
Inline: False
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
**Symbols:**

```
ffffffff814a06c0-ffffffff814a0773: keyctl_pkey_params_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int keyctl_pkey_params_parse(struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff814be090)
Location: security/keys/keyctl_pkey.c:38
Inline: False
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
**Symbols:**

```
ffffffff814be090-ffffffff814be143: keyctl_pkey_params_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff814c3f59)
Location: security/keys/keyctl_pkey.c:38
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff8151c929)
Location: security/keys/keyctl_pkey.c:38
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff815afadc)
Location: security/keys/keyctl_pkey.c:38
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff8165a2fc)
Location: security/keys/keyctl_pkey.c:38
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff81692bcc)
Location: security/keys/keyctl_pkey.c:38
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff816cf19c)
Location: security/keys/keyctl_pkey.c:38
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
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
In security/keys/keyctl_pkey.c (ffff800010538c54)
Location: security/keys/keyctl_pkey.c:38
Inline: True
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
In security/keys/keyctl_pkey.c (c06ef714)
Location: security/keys/keyctl_pkey.c:38
Inline: True
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
In security/keys/keyctl_pkey.c (c000000000687bac)
Location: security/keys/keyctl_pkey.c:38
Inline: True
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
In security/keys/keyctl_pkey.c (ffffffe0003978c4)
Location: security/keys/keyctl_pkey.c:38
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff81446cd8)
Location: security/keys/keyctl_pkey.c:38
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff81437728)
Location: security/keys/keyctl_pkey.c:38
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff81442d78)
Location: security/keys/keyctl_pkey.c:38
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff8145a0a8)
Location: security/keys/keyctl_pkey.c:38
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
