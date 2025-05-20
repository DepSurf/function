# Function: <code>get_instantiation_keyring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff81331cf0)
Location: security/keys/keyctl.c:943
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_reject_key
```
**Symbols:**

```
ffffffff81331cf0-ffffffff81331d70: get_instantiation_keyring.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff81366ab0)
Location: security/keys/keyctl.c:971
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff81366ab0-ffffffff81366b30: get_instantiation_keyring.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff8137d2d0)
Location: security/keys/keyctl.c:971
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff8137d2d0-ffffffff8137d350: get_instantiation_keyring.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff813910c0)
Location: security/keys/keyctl.c:976
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff813910c0-ffffffff81391140: get_instantiation_keyring.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff813b6670)
Location: security/keys/keyctl.c:980
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff813b6670-ffffffff813b66f6: get_instantiation_keyring.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff813e6e70)
Location: security/keys/keyctl.c:980
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff813e6e70-ffffffff813e6efb: get_instantiation_keyring.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff81401670)
Location: security/keys/keyctl.c:980
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff81401670-ffffffff814016fb: get_instantiation_keyring.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff8142e180)
Location: security/keys/keyctl.c:1036
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff8142e180-ffffffff8142e205: get_instantiation_keyring.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff81447eb0)
Location: security/keys/keyctl.c:1036
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff81447eb0-ffffffff81447f35: get_instantiation_keyring.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int get_instantiation_keyring(key_serial_t ringid, struct request_key_auth *rka, struct key **_dest_keyring);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814997e0)
Location: security/keys/keyctl.c:1107
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff814997e0-ffffffff81499895: get_instantiation_keyring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int get_instantiation_keyring(key_serial_t ringid, struct request_key_auth *rka, struct key **_dest_keyring);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814b7270)
Location: security/keys/keyctl.c:1107
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff814b7270-ffffffff814b7325: get_instantiation_keyring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int get_instantiation_keyring(key_serial_t ringid, struct request_key_auth *rka, struct key **_dest_keyring);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814bd0d0)
Location: security/keys/keyctl.c:1107
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff814bd0d0-ffffffff814bd185: get_instantiation_keyring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int get_instantiation_keyring(key_serial_t ringid, struct request_key_auth *rka, struct key **_dest_keyring);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81515b50)
Location: security/keys/keyctl.c:1107
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff81515b50-ffffffff81515c05: get_instantiation_keyring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int get_instantiation_keyring(key_serial_t ringid, struct request_key_auth *rka, struct key **_dest_keyring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff815a8360)
Location: security/keys/keyctl.c:1107
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff815a8360-ffffffff815a8420: get_instantiation_keyring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int get_instantiation_keyring(key_serial_t ringid, struct request_key_auth *rka, struct key **_dest_keyring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81652470)
Location: security/keys/keyctl.c:1107
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff81652470-ffffffff81652530: get_instantiation_keyring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int get_instantiation_keyring(key_serial_t ringid, struct request_key_auth *rka, struct key **_dest_keyring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8168ac90)
Location: security/keys/keyctl.c:1112
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff8168ac90-ffffffff8168ad50: get_instantiation_keyring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int get_instantiation_keyring(key_serial_t ringid, struct request_key_auth *rka, struct key **_dest_keyring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff816c7190)
Location: security/keys/keyctl.c:1112
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff816c7190-ffffffff816c7250: get_instantiation_keyring (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffff800010531900)
Location: security/keys/keyctl.c:1036
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffff800010531900-ffff8000105319b4: get_instantiation_keyring.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long int get_instantiation_keyring(key_serial_t ringid, struct request_key_auth *rka, struct key **_dest_keyring);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (c06e95ac)
Location: security/keys/keyctl.c:1036
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
c06e95ac-c06e9638: get_instantiation_keyring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (c00000000067f090)
Location: security/keys/keyctl.c:1036
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
c00000000067f090-c00000000067f190: get_instantiation_keyring.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffe0003927bc)
Location: security/keys/keyctl.c:1036
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffe0003927bc-ffffffe000392846: get_instantiation_keyring.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff81440490)
Location: security/keys/keyctl.c:1036
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff81440490-ffffffff81440515: get_instantiation_keyring.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff81430f00)
Location: security/keys/keyctl.c:1036
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff81430f00-ffffffff81430f85: get_instantiation_keyring.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff8143c630)
Location: security/keys/keyctl.c:1036
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff8143c630-ffffffff8143c6b5: get_instantiation_keyring.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff814537c0)
Location: security/keys/keyctl.c:1036
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff814537c0-ffffffff81453845: get_instantiation_keyring.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
