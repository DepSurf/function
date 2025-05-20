# Function: <code>request_asymmetric_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff813967f2)
Location: security/integrity/digsig_asymmetric.c:26
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff813d2580)
Location: security/integrity/digsig_asymmetric.c:28
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff813e9ca8)
Location: security/integrity/digsig_asymmetric.c:28
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff813f60a8)
Location: security/integrity/digsig_asymmetric.c:28
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff8141e1a8)
Location: security/integrity/digsig_asymmetric.c:28
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff81450460)
Location: security/integrity/digsig_asymmetric.c:28
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff8146d400)
Location: security/integrity/digsig_asymmetric.c:28
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
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
In security/integrity/digsig_asymmetric.c (ffffffff8149aaf2)
Location: security/integrity/digsig_asymmetric.c:24
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
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
In security/integrity/digsig_asymmetric.c (ffffffff814b4d42)
Location: security/integrity/digsig_asymmetric.c:24
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct key *request_asymmetric_key(struct key *keyring, uint32_t keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/digsig_asymmetric.c (0)
Location: security/integrity/digsig_asymmetric.c:22
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
**Symbols:**

```
ffffffff81514220-ffffffff81514357: request_asymmetric_key (STB_LOCAL)
ffffffff815144dc-ffffffff815144f4: request_asymmetric_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct key *request_asymmetric_key(struct key *keyring, uint32_t keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/digsig_asymmetric.c (0)
Location: security/integrity/digsig_asymmetric.c:22
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
**Symbols:**

```
ffffffff81531380-ffffffff815314e0: request_asymmetric_key (STB_LOCAL)
ffffffff81bf1a07-ffffffff81bf1a3e: request_asymmetric_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct key *request_asymmetric_key(struct key *keyring, uint32_t keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/digsig_asymmetric.c (0)
Location: security/integrity/digsig_asymmetric.c:22
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
**Symbols:**

```
ffffffff815397b0-ffffffff8153990d: request_asymmetric_key (STB_LOCAL)
ffffffff81be3a25-ffffffff81be3a5c: request_asymmetric_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct key *request_asymmetric_key(struct key *keyring, uint32_t keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/digsig_asymmetric.c (0)
Location: security/integrity/digsig_asymmetric.c:22
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
**Symbols:**

```
ffffffff81598100-ffffffff81598257: request_asymmetric_key (STB_LOCAL)
ffffffff81cd6be9-ffffffff81cd6c20: request_asymmetric_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct key *request_asymmetric_key(struct key *keyring, uint32_t keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/digsig_asymmetric.c (0)
Location: security/integrity/digsig_asymmetric.c:22
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
**Symbols:**

```
ffffffff8163c970-ffffffff8163cacd: request_asymmetric_key (STB_LOCAL)
ffffffff81e89e1c-ffffffff81e89e6d: request_asymmetric_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct key *request_asymmetric_key(struct key *keyring, uint32_t keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff816f4210)
Location: security/integrity/digsig_asymmetric.c:22
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
**Symbols:**

```
ffffffff816f4210-ffffffff816f43b0: request_asymmetric_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct key *request_asymmetric_key(struct key *keyring, uint32_t keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff8172e340)
Location: security/integrity/digsig_asymmetric.c:22
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
**Symbols:**

```
ffffffff8172e340-ffffffff8172e4da: request_asymmetric_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct key *request_asymmetric_key(struct key *keyring, uint32_t keyid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff8176eca0)
Location: security/integrity/digsig_asymmetric.c:22
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
**Symbols:**

```
ffffffff8176eca0-ffffffff8176ee3a: request_asymmetric_key (STB_LOCAL)
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
In security/integrity/digsig_asymmetric.c (ffff8000105acf00)
Location: security/integrity/digsig_asymmetric.c:24
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
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
In security/integrity/digsig_asymmetric.c (c075c768)
Location: security/integrity/digsig_asymmetric.c:24
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
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
In security/integrity/digsig_asymmetric.c (c00000000072b498)
Location: security/integrity/digsig_asymmetric.c:24
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
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
In security/integrity/digsig_asymmetric.c (ffffffe0003f54e0)
Location: security/integrity/digsig_asymmetric.c:24
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
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
In security/integrity/digsig_asymmetric.c (ffffffff814ad322)
Location: security/integrity/digsig_asymmetric.c:24
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
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
In security/integrity/digsig_asymmetric.c (ffffffff8149dd42)
Location: security/integrity/digsig_asymmetric.c:24
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
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
In security/integrity/digsig_asymmetric.c (ffffffff814a93c2)
Location: security/integrity/digsig_asymmetric.c:24
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
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
In security/integrity/digsig_asymmetric.c (ffffffff814c1dd2)
Location: security/integrity/digsig_asymmetric.c:24
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
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
