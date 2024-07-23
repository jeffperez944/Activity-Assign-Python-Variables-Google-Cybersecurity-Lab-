<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Introduction">Introduction</a></h2><p>Variables help security analysts to keep track of a variety of security-related information. For example, analysts may need to create Python variables for the users who are allowed to log in, the number of login attempts that they're permitted, and the current number of attempts that a user has made.</p>
<p>In this lab, you'll practice assigning values to variables and determining their data types.</p>

</div>
</div>


</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Task-1">Task 1</a></h2><p>In your work as an analyst, imagine there is a device only users specified on an allow list can access, and its device ID is <code>"72e08x0"</code>.</p>
<p>In the following code cell, assign this value to a variable named <code>device_id</code>. Then, display the contents of the variable and observe the output.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Assign the `device_id` variable to the device ID that only specified users can access</span>

<span class="n">device_id</span> <span class="o">=</span> <span class="s2">"72e08x0"</span>

<span class="c1"># Display `device_id`</span>

<span class="nb">print</span><span class="p">(</span><span class="n">device_id</span><span class="p">)</span>
</pre></div>


</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">




<div class="output_subarea output_stream output_stdout output_text">
<pre>72e08x0
</pre>


</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Task-2">Task 2</a></h2><p>Now that the variable <code>device_id</code> is defined, you can return its data type.</p>
<p>In this task, use a Python function to find the data type of the variable <code>device_id</code>. Store the data type in another variable called <code>device_id_type</code>. Then, display <code>device_id_type</code> to examine the output.</p>
  

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Assign the `device_id` variable to the device ID that only specified users can access</span>

<span class="n">device_id</span> <span class="o">=</span> <span class="s2">"72e08x0"</span>

<span class="c1"># Assign `device_id_type` to the data type of `device_id`</span>

<span class="n">device_id_type</span> <span class="o">=</span> <span class="s2">"72e08x0"</span>

<span class="c1"># Display `device_id_type`</span>

<span class="nb">print</span><span class="p">(</span><span class="n">device_id_type</span><span class="p">)</span>
    
</pre></div>

</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">



<div class="output_subarea output_stream output_stdout output_text">
<pre>72e08x0
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Task-3">Task 3</a></h2><p>As you continue your work, you're provided a list of usernames of users who are allowed to access the device. The usernames with this access are <code>"madebowa"</code>, <code>"jnguyen"</code>, <code>"tbecker"</code>, <code>"nhersh"</code>, and <code>"redwards"</code>.</p>
<p>In this task, create a variable called <code>username_list</code>. Assign a list with the approved usernames to this variable. Then, display the value of the <code>username_list</code> variable.</p>
  

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Assign `username_list` to the list of usernames who are allowed to access the device</span>

<span class="n">username_list</span> <span class="o">=</span> <span class="p">[</span><span class="s2">"madebowa"</span><span class="p">,</span> <span class="s2">"jnguyen"</span><span class="p">,</span> <span class="s2">"tbecker"</span><span class="p">,</span> <span class="s2">"nhersh"</span><span class="p">,</span> <span class="s2">"redwards"</span><span class="p">]</span>

<span class="c1"># Display `username_list`</span>

<span class="nb">print</span><span class="p">(</span><span class="n">username_list</span><span class="p">)</span>
</pre></div>

</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">



<div class="output_subarea output_stream output_stdout output_text">
<pre>['madebowa', 'jnguyen', 'tbecker', 'nhersh', 'redwards']
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Task-4">Task 4</a></h2><p>In this task, find the data type of the <code>username_list</code>. Store the type in a variable called <code>username_list_type</code>. Then, display <code>username_list_type</code> to examine the output.</p>
  

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">max_logins</span> <span class="o">=</span> <span class="mi">3</span>
<span class="n">max_logins_type</span> <span class="o">=</span> <span class="nb">type</span><span class="p">(</span><span class="n">max_logins</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">max_logins_type</span><span class="p">)</span>
</pre></div>


</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

 


<div class="output_subarea output_stream output_stdout output_text">
<pre>&lt;class 'int'&gt;
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Task-5">Task 5</a></h2><p>Now, imagine that you've been informed that the previous list is not up-to-date and that there is another employee that now has access to the device. You're given the updated list of usernames with access, including the new employee, as follows: <code>"madebowa"</code>, <code>"jnguyen"</code>, <code>"tbecker"</code>, <code>"nhersh"</code>, <code>"redwards"</code>, and <code>"lpope"</code>.</p>
<p>In this task, reassign the variable <code>username_list</code> to the new list. Run the code to display the list before and after it's been updated to observe the difference.</p>
  

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Assign `username_list` to the list of usernames who are allowed to access the device</span>

<span class="n">username_list</span> <span class="o">=</span> <span class="p">[</span><span class="s2">"madebowa"</span><span class="p">,</span> <span class="s2">"jnguyen"</span><span class="p">,</span> <span class="s2">"tbecker"</span><span class="p">,</span> <span class="s2">"nhersh"</span><span class="p">,</span> <span class="s2">"redwards"</span><span class="p">]</span>

<span class="c1"># Display `username_list`</span>

<span class="nb">print</span><span class="p">(</span><span class="n">username_list</span><span class="p">)</span>

<span class="c1"># Assign `username_list` to the updated list of usernames who are allowed to access the device</span>

<span class="n">username_list</span> <span class="o">=</span> <span class="p">[</span><span class="s2">"madebowa"</span><span class="p">,</span> <span class="s2">"jnguyen"</span><span class="p">,</span> <span class="s2">"tbecker"</span><span class="p">,</span> <span class="s2">"nhersh"</span><span class="p">,</span> <span class="s2">"redwards"</span><span class="p">,</span> <span class="s2">"lpope"</span><span class="p">]</span>

<span class="c1"># Display `username_list`</span>

<span class="nb">print</span><span class="p">(</span><span class="n">username_list</span><span class="p">)</span>
</pre></div>

</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">




<div class="output_subarea output_stream output_stdout output_text">
<pre>['madebowa', 'jnguyen', 'tbecker', 'nhersh', 'redwards']
['madebowa', 'jnguyen', 'tbecker', 'nhersh', 'redwards', 'lpope']
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Task-6">Task 6</a></h2><p>In this task, define a variable called <code>max_logins</code> that represents the maximum number of login attempts allowed per user. Store the value <code>3</code> in this variable. Then, store its data type in another variable called <code>max_logins_type</code>. Display <code>max_logins_type</code> to examine the output.</p>
  

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Assign `max_logins` to the value 3</span>

<span class="n">max_logins</span> <span class="o">=</span> <span class="mi">3</span>

<span class="c1"># Assign `max_logins_type` to the data type of `max_logins`</span>

<span class="n">max_logins_type</span> <span class="o">=</span> <span class="nb">type</span><span class="p">(</span><span class="n">max_logins</span><span class="p">)</span>

<span class="c1"># Display `max_logins_type`</span>

<span class="nb">print</span><span class="p">(</span><span class="n">max_logins_type</span><span class="p">)</span>
</pre></div>


</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

 


<div class="output_subarea output_stream output_stdout output_text">
<pre>&lt;class 'int'&gt;
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Task-7">Task 7</a></h2><p>In this task, define a variable called <code>login_attempts</code> that represents the current number of login attempts made by a user. Store the value <code>2</code> in this variable. Then, store its data type in a variable called <code>login_attempts_type</code>. Display <code>login_attempts_type</code> to observe the output.</p>
  

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Assign `login_attempts` to the value 2</span>

<span class="n">login_attempts</span> <span class="o">=</span> <span class="mi">2</span>

<span class="c1"># Assign `login_attempts_type` to the data type of `login_attempts`</span>

<span class="n">login_attempts_type</span> <span class="o">=</span> <span class="nb">type</span><span class="p">(</span><span class="n">login_attempts</span><span class="p">)</span>

<span class="c1"># Display `login_attempts_type`</span>

<span class="nb">print</span><span class="p">(</span><span class="n">login_attempts_type</span><span class="p">)</span>
</pre></div>


</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">




<div class="output_subarea output_stream output_stdout output_text">
<pre>&lt;class 'int'&gt;
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Task-8">Task 8</a></h2><p>In this task, you'll determine the Boolean value that represents whether the current number of login attempts a user has made is less than or equal to the maximum number of login attempts allowed.</p>
  

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Assign `max_logins` to the value 3</span>

<span class="n">max_logins</span> <span class="o">=</span> <span class="mi">3</span>

<span class="c1"># Assign `login_attempts` to the value 2</span>

<span class="n">login_attempts</span> <span class="o">=</span> <span class="mi">2</span>

<span class="c1"># Determine whether the current number of login attempts a user has made is less than or equal to the maximum number of login attempts allowed,</span>
<span class="c1"># and display the resulting Boolean value</span>

<span class="nb">print</span><span class="p">(</span><span class="n">login_attempts</span> <span class="o">&lt;=</span> <span class="n">max_logins</span><span class="p">)</span>
    
</pre></div>


</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">




<div class="output_subarea output_stream output_stdout output_text">
<pre>True
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Task-9">Task 9</a></h2><p>This code continues to check for the Boolean value of whether <code>max_logins</code> is less than or equal to <code>login_attempts</code>. In this task, reassign other values to <code>login_attempts</code>. For example, you might choose a value that is higher than the maximum number of attempts allowed. Observe how the output changes.</p>
  

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Assign `max_logins` to the value 3</span>

<span class="n">max_logins</span> <span class="o">=</span> <span class="mi">3</span>

<span class="c1"># Assign `login_attempts` to a specific value</span>

<span class="n">login_attempts</span> <span class="o">=</span> <span class="mi">3</span>

<span class="c1"># Determine whether the current number of login attempts a user has made is less than or equal to the maximum number of login attempts allowed,</span>
<span class="c1"># and display the resulting Boolean value</span>

<span class="nb">print</span><span class="p">(</span><span class="n">login_attempts</span> <span class="o">&lt;=</span> <span class="n">max_logins</span><span class="p">)</span>
</pre></div>


</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">




<div class="output_subarea output_stream output_stdout output_text">
<pre>True
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Task-10">Task 10</a></h2><p>Finally, you can also assign a Boolean value of <code>True</code> or <code>False</code> to a variable.</p>
<p>In this task, you'll create a variable called <code>login_status</code>, which is a Boolean that represents whether a user is logged in. Assign <code>False</code> to this variable and store its data type in a variable called <code>login_status_type</code> and display it.</p>
  

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Assign `login_status` to the Boolean value False</span>

<span class="n">login_status</span> <span class="o">=</span> <span class="kc">False</span>

<span class="c1"># Assign `login_status_type` to the data type of `login_status`</span>

<span class="n">login_status_type</span> <span class="o">=</span> <span class="nb">type</span><span class="p">(</span><span class="n">login_status</span><span class="p">)</span>

<span class="c1"># Display `login_status_type`</span>

<span class="nb">print</span><span class="p">(</span><span class="n">login_status_type</span><span class="p">)</span>
</pre></div>

</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">




<div class="output_subarea output_stream output_stdout output_text">
<pre>&lt;class 'bool'&gt;
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">

</div>
</div>
</div>
    </div>
