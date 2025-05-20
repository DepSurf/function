# Function: <code>cpuhp_store_callbacks</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpuhp_store_callbacks(enum cpuhp_state state, const char *name, int (*startup)(unsigned int), int (*teardown)(unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81083660)
Location: kernel/cpu.c:1376
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_setup_state
```
**Symbols:**

```
ffffffff81083660-ffffffff810836c8: cpuhp_store_callbacks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpuhp_store_callbacks(enum cpuhp_state state, const char *name, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81088230)
Location: kernel/cpu.c:1327
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_setup_state
```
**Symbols:**

```
ffffffff81088230-ffffffff8108834f: cpuhp_store_callbacks (STB_LOCAL)
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
In kernel/cpu.c (ffffffff810865e3)
Location: kernel/cpu.c:1246
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffff8108d254)
Location: kernel/cpu.c:1430
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffff81090c2a)
Location: kernel/cpu.c:1512
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffff81098cea)
Location: kernel/cpu.c:1534
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffff8109d279)
Location: kernel/cpu.c:1560
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffff810a37c9)
Location: kernel/cpu.c:1575
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffff810aa858)
Location: kernel/cpu.c:1706
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffff810a60e8)
Location: kernel/cpu.c:1717
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffff810a6f38)
Location: kernel/cpu.c:1821
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffff810b88b3)
Location: kernel/cpu.c:1851
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffff810cf161)
Location: kernel/cpu.c:1873
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffff810ed5af)
Location: kernel/cpu.c:1897
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffff810f913f)
Location: kernel/cpu.c:2282
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffff8110254f)
Location: kernel/cpu.c:2328
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffff8000100f8fd8)
Location: kernel/cpu.c:1575
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (c0357224)
Location: kernel/cpu.c:1575
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (c00000000013fc00)
Location: kernel/cpu.c:1575
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffe0000c3bcc)
Location: kernel/cpu.c:1575
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffff8109d0e9)
Location: kernel/cpu.c:1575
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffff8108bb19)
Location: kernel/cpu.c:1575
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffff8109d099)
Location: kernel/cpu.c:1575
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
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
In kernel/cpu.c (ffffffff810a4ec9)
Location: kernel/cpu.c:1575
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool multi_instance</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
</ul>
