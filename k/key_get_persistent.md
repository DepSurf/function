# Function: <code>key_get_persistent</code>

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
In security/keys/persistent.c (ffffffff813362cc)
Location: security/keys/persistent.c:75
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
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
In security/keys/persistent.c (ffffffff8136b29f)
Location: security/keys/persistent.c:75
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
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
In security/keys/persistent.c (ffffffff81381aaf)
Location: security/keys/persistent.c:75
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
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
In security/keys/persistent.c (ffffffff813959ea)
Location: security/keys/persistent.c:77
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
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
In security/keys/persistent.c (ffffffff813bb16a)
Location: security/keys/persistent.c:77
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
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
In security/keys/persistent.c (ffffffff813ebf4a)
Location: security/keys/persistent.c:77
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
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
In security/keys/persistent.c (ffffffff81406b4a)
Location: security/keys/persistent.c:77
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
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
In security/keys/persistent.c (ffffffff81433cca)
Location: security/keys/persistent.c:73
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
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
In security/keys/persistent.c (ffffffff8144da3a)
Location: security/keys/persistent.c:73
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int key_get_persistent(struct user_namespace *ns, kuid_t uid, key_ref_t dest_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/persistent.c (ffffffff8149f890)
Location: security/keys/persistent.c:73
Inline: False
Direct callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff8149f890-ffffffff8149fad5: key_get_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int key_get_persistent(struct user_namespace *ns, kuid_t uid, key_ref_t dest_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/persistent.c (ffffffff814bd2c0)
Location: security/keys/persistent.c:73
Inline: False
Direct callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff814bd2c0-ffffffff814bd505: key_get_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int key_get_persistent(struct user_namespace *ns, kuid_t uid, key_ref_t dest_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/persistent.c (ffffffff814c3130)
Location: security/keys/persistent.c:73
Inline: False
Direct callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff814c3130-ffffffff814c3371: key_get_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int key_get_persistent(struct user_namespace *ns, kuid_t uid, key_ref_t dest_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/persistent.c (ffffffff8151bb20)
Location: security/keys/persistent.c:73
Inline: False
Direct callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff8151bb20-ffffffff8151bd61: key_get_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int key_get_persistent(struct user_namespace *ns, kuid_t uid, key_ref_t dest_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/persistent.c (ffffffff815aed50)
Location: security/keys/persistent.c:73
Inline: False
Direct callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff815aed50-ffffffff815aefc6: key_get_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int key_get_persistent(struct user_namespace *ns, kuid_t uid, key_ref_t dest_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/persistent.c (ffffffff81659510)
Location: security/keys/persistent.c:73
Inline: False
Direct callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff81659510-ffffffff81659786: key_get_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int key_get_persistent(struct user_namespace *ns, kuid_t uid, key_ref_t dest_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/persistent.c (ffffffff81691da0)
Location: security/keys/persistent.c:73
Inline: False
Direct callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff81691da0-ffffffff81692026: key_get_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int key_get_persistent(struct user_namespace *ns, kuid_t uid, key_ref_t dest_ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/persistent.c (ffffffff816ce370)
Location: security/keys/persistent.c:73
Inline: False
Direct callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff816ce370-ffffffff816ce5f6: key_get_persistent (STB_LOCAL)
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
In security/keys/persistent.c (ffff800010537be0)
Location: security/keys/persistent.c:73
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
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
In security/keys/persistent.c (c06ee9e0)
Location: security/keys/persistent.c:73
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
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
In security/keys/persistent.c (c000000000686c70)
Location: security/keys/persistent.c:73
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
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
In security/keys/persistent.c (ffffffe000396dbe)
Location: security/keys/persistent.c:73
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
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
In security/keys/persistent.c (ffffffff8144601a)
Location: security/keys/persistent.c:73
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
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
In security/keys/persistent.c (ffffffff81436a6a)
Location: security/keys/persistent.c:73
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
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
In security/keys/persistent.c (ffffffff814420ba)
Location: security/keys/persistent.c:73
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
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
In security/keys/persistent.c (ffffffff814593ea)
Location: security/keys/persistent.c:73
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
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
