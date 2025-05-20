# Function: <code>__list_remove_profile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __list_remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8137f130)
Location: security/apparmor/policy.c:144
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
**Symbols:**

```
ffffffff8137f130-ffffffff8137f210: __list_remove_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __list_remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813b88a0)
Location: security/apparmor/policy.c:158
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
**Symbols:**

```
ffffffff813b88a0-ffffffff813b89ad: __list_remove_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __list_remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813cfc40)
Location: security/apparmor/policy.c:158
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
**Symbols:**

```
ffffffff813cfc40-ffffffff813cfd51: __list_remove_profile (STB_LOCAL)
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
In security/apparmor/policy.c (ffffffff813e3a55)
Location: security/apparmor/policy.c:143
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
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
In security/apparmor/policy.c (ffffffff8140a857)
Location: security/apparmor/policy.c:143
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
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
In security/apparmor/policy.c (ffffffff8143c063)
Location: security/apparmor/policy.c:143
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
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
In security/apparmor/policy.c (ffffffff81458ed3)
Location: security/apparmor/policy.c:143
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
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
In security/apparmor/policy.c (ffffffff81486659)
Location: security/apparmor/policy.c:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
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
In security/apparmor/policy.c (ffffffff814a0509)
Location: security/apparmor/policy.c:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814fc37c)
Location: security/apparmor/policy.c:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__aa_profile_list_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff815195ec)
Location: security/apparmor/policy.c:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__aa_profile_list_release
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
In security/apparmor/policy.c (ffffffff8151fef4)
Location: security/apparmor/policy.c:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__aa_profile_list_release
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
In security/apparmor/policy.c (ffffffff8157e094)
Location: security/apparmor/policy.c:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__aa_profile_list_release
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
In security/apparmor/policy.c (ffffffff8161c806)
Location: security/apparmor/policy.c:140
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__aa_profile_list_release
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
In security/apparmor/policy.c (ffffffff816cfaa6)
Location: security/apparmor/policy.c:142
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__aa_profile_list_release
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
In security/apparmor/policy.c (ffffffff817086c6)
Location: security/apparmor/policy.c:179
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__aa_profile_list_release
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
In security/apparmor/policy.c (ffffffff81746156)
Location: security/apparmor/policy.c:180
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__aa_profile_list_release
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
In security/apparmor/policy.c (ffff8000105962c0)
Location: security/apparmor/policy.c:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
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
In security/apparmor/policy.c (c07473a4)
Location: security/apparmor/policy.c:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
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
In security/apparmor/policy.c (c00000000070bd10)
Location: security/apparmor/policy.c:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __list_remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffe0003e2b68)
Location: security/apparmor/policy.c:138
Inline: False
Direct callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
**Symbols:**

```
ffffffe0003e2b68-ffffffe0003e2bbc: __list_remove_profile (STB_LOCAL)
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
In security/apparmor/policy.c (ffffffff81498ae9)
Location: security/apparmor/policy.c:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
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
In security/apparmor/policy.c (ffffffff81489509)
Location: security/apparmor/policy.c:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
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
In security/apparmor/policy.c (ffffffff81494b89)
Location: security/apparmor/policy.c:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
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
In security/apparmor/policy.c (ffffffff814acba9)
Location: security/apparmor/policy.c:138
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__remove_profile
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
