# Function: <code>security_watch_key</code>

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
int security_watch_key(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814abd60)
Location: security/security.c:2454
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff814abd60-ffffffff814abd9a: security_watch_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_watch_key(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c9360)
Location: security/security.c:2471
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff814c9360-ffffffff814c939a: security_watch_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_watch_key(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cf990)
Location: security/security.c:2534
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff814cf990-ffffffff814cf9ca: security_watch_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_watch_key(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815286c0)
Location: security/security.c:2542
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff815286c0-ffffffff815286fa: security_watch_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_watch_key(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bd8a0)
Location: security/security.c:2572
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff815bd8a0-ffffffff815bd8ed: security_watch_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_watch_key(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816698d0)
Location: security/security.c:2552
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff816698d0-ffffffff8166991d: security_watch_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_watch_key(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a1eb0)
Location: security/security.c:4301
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff816a1eb0-ffffffff816a1efd: security_watch_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_watch_key(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dea20)
Location: security/security.c:4462
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff816dea20-ffffffff816dea6d: security_watch_key (STB_GLOBAL)
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
