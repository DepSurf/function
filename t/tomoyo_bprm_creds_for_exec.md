# Function: <code>tomoyo_bprm_creds_for_exec</code>

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
int tomoyo_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff814e9990)
Location: security/tomoyo/tomoyo.c:72
Inline: False
```
**Symbols:**

```
ffffffff814e9990-ffffffff814e99b2: tomoyo_bprm_creds_for_exec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff81506cb0)
Location: security/tomoyo/tomoyo.c:72
Inline: False
```
**Symbols:**

```
ffffffff81506cb0-ffffffff81506cd2: tomoyo_bprm_creds_for_exec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tomoyo_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/tomoyo.c (ffffffff8150d7f0)
Location: security/tomoyo/tomoyo.c:72
Inline: False
```
**Symbols:**

```
ffffffff8150d7f0-ffffffff8150d812: tomoyo_bprm_creds_for_exec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tomoyo_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/tomoyo.c (0)
Location: security/tomoyo/tomoyo.c:72
Inline: False
```
**Symbols:**

```
ffffffff8156b330-ffffffff8156b36e: tomoyo_bprm_creds_for_exec (STB_LOCAL)
ffffffff81cd618e-ffffffff81cd61a3: tomoyo_bprm_creds_for_exec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tomoyo_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/tomoyo.c (0)
Location: security/tomoyo/tomoyo.c:72
Inline: False
```
**Symbols:**

```
ffffffff81607520-ffffffff8160756e: tomoyo_bprm_creds_for_exec (STB_LOCAL)
ffffffff81e88f74-ffffffff81e88f89: tomoyo_bprm_creds_for_exec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tomoyo_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/tomoyo.c (0)
Location: security/tomoyo/tomoyo.c:73
Inline: False
```
**Symbols:**

```
ffffffff816b8c40-ffffffff816b8c8e: tomoyo_bprm_creds_for_exec (STB_LOCAL)
ffffffff82074a05-ffffffff82074a1a: tomoyo_bprm_creds_for_exec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tomoyo_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/tomoyo.c (0)
Location: security/tomoyo/tomoyo.c:73
Inline: False
```
**Symbols:**

```
ffffffff816f1610-ffffffff816f165e: tomoyo_bprm_creds_for_exec (STB_LOCAL)
ffffffff820f455c-ffffffff820f4571: tomoyo_bprm_creds_for_exec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tomoyo_bprm_creds_for_exec(struct linux_binprm *bprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/tomoyo.c (0)
Location: security/tomoyo/tomoyo.c:73
Inline: False
```
**Symbols:**

```
ffffffff8172e3e0-ffffffff8172e42e: tomoyo_bprm_creds_for_exec (STB_LOCAL)
ffffffff821d19a1-ffffffff821d19b6: tomoyo_bprm_creds_for_exec.cold (STB_LOCAL)
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
