# Function: <code>trust_moklist</code>

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
bool trust_moklist();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/machine_keyring.c (ffffffff8349d203)
Location: security/integrity/platform_certs/machine_keyring.c:65
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_init_keyring
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_mok
```
**Symbols:**

```
ffffffff8349d203-ffffffff8349d275: trust_moklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool trust_moklist();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/machine_keyring.c (ffffffff83ed4d10)
Location: security/integrity/platform_certs/machine_keyring.c:65
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_init_keyring
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_mok
```
**Symbols:**

```
ffffffff83ed4d10-ffffffff83ed4da1: trust_moklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool trust_moklist();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/machine_keyring.c (ffffffff836f9e70)
Location: security/integrity/platform_certs/machine_keyring.c:65
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_init_keyring
  - security/integrity/platform_certs/keyring_handler.c:get_handler_for_mok
```
**Symbols:**

```
ffffffff836f9e70-ffffffff836f9f01: trust_moklist (STB_GLOBAL)
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
In security/integrity/platform_certs/machine_keyring.c (ffffffff8392d35e)
Location: security/integrity/platform_certs/machine_keyring.c:64
Inline: True
Inline callers:
  - security/integrity/platform_certs/machine_keyring.c:imputed_trust_enabled
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
</ul>
