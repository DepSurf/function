# Function: <code>jump_label_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8118acb0)
Location: kernel/jump_label.c:465
Inline: False
```
**Symbols:**

```
ffffffff8118acb0-ffffffff8118ad3f: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8119d320)
Location: kernel/jump_label.c:554
Inline: False
```
**Symbols:**

```
ffffffff8119d320-ffffffff8119d3af: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811accf0)
Location: kernel/jump_label.c:561
Inline: False
```
**Symbols:**

```
ffffffff811accf0-ffffffff811acd7f: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811b4330)
Location: kernel/jump_label.c:666
Inline: True
```
**Symbols:**

```
ffffffff811b4330-ffffffff811b43e9: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811c80d0)
Location: kernel/jump_label.c:720
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
```
**Symbols:**

```
ffffffff811c80d0-ffffffff811c8189: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811e84d0)
Location: kernel/jump_label.c:739
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
```
**Symbols:**

```
ffffffff811e84d0-ffffffff811e8582: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811f9190)
Location: kernel/jump_label.c:731
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
**Symbols:**

```
ffffffff811f9190-ffffffff811f924c: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81211110)
Location: kernel/jump_label.c:785
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
**Symbols:**

```
ffffffff81211110-ffffffff812111cb: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8121ed50)
Location: kernel/jump_label.c:787
Inline: True
```
**Symbols:**

```
ffffffff8121ed50-ffffffff8121ee0b: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8124ac00)
Location: kernel/jump_label.c:787
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
**Symbols:**

```
ffffffff8124ac00-ffffffff8124acb6: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81254fe0)
Location: kernel/jump_label.c:801
Inline: False
Direct callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
**Symbols:**

```
ffffffff81254fe0-ffffffff812550a5: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812594e0)
Location: kernel/jump_label.c:804
Inline: False
Direct callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
**Symbols:**

```
ffffffff812594e0-ffffffff812595ae: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81295090)
Location: kernel/jump_label.c:806
Inline: False
Direct callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
**Symbols:**

```
ffffffff81295090-ffffffff8129516c: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812eade0)
Location: kernel/jump_label.c:806
Inline: False
Direct callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
**Symbols:**

```
ffffffff812eade0-ffffffff812eaef8: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81354df0)
Location: kernel/jump_label.c:805
Inline: False
Direct callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
**Symbols:**

```
ffffffff81354df0-ffffffff81354f08: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff813862e0)
Location: kernel/jump_label.c:805
Inline: False
Direct callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
**Symbols:**

```
ffffffff813862e0-ffffffff813863f8: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff813af7a0)
Location: kernel/jump_label.c:805
Inline: False
Direct callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
**Symbols:**

```
ffffffff813af7a0-ffffffff813af8b8: jump_label_update (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffff8000102aaf10)
Location: kernel/jump_label.c:787
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
```
**Symbols:**

```
ffff8000102aaf10-ffff8000102ab00c: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (c00000000035ea70)
Location: kernel/jump_label.c:787
Inline: True
Direct callers:
  - kernel/jump_label.c:static_key_enable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
**Symbols:**

```
c00000000035ea70-c00000000035ebc8: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812173a0)
Location: kernel/jump_label.c:787
Inline: True
```
**Symbols:**

```
ffffffff812173a0-ffffffff8121745b: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8120a100)
Location: kernel/jump_label.c:787
Inline: True
```
**Symbols:**

```
ffffffff8120a100-ffffffff8120a1bb: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81215140)
Location: kernel/jump_label.c:787
Inline: True
```
**Symbols:**

```
ffffffff81215140-ffffffff812151fb: jump_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void jump_label_update(struct static_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81224110)
Location: kernel/jump_label.c:787
Inline: True
```
**Symbols:**

```
ffffffff81224110-ffffffff812241e9: jump_label_update (STB_LOCAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
