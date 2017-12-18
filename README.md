<!DOCTYPE html>
<html class="" lang="en">
<head prefix="og: http://ogp.me/ns#">
<meta charset="utf-8">
<meta content="IE=edge" http-equiv="X-UA-Compatible">
<meta content="object" property="og:type">
<meta content="GitLab" property="og:site_name">
<meta content="Homework/05-Matplotlib/Instructions/README.md · master · GW-Coding-Boot-Camp / 10-16-2017-GW-Arlington-Class-Repository-DATA" property="og:title">
<meta content="GitLab Community Edition" property="og:description">
<meta content="http://gw.bootcampcontent.com/assets/gitlab_logo-7ae504fe4f68fdebb3c2034e36621930cd36ea87924c11ff65dbcb8ed50dca58.png" property="og:image">
<meta content="http://gw.bootcampcontent.com/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/blob/master/Homework/05-Matplotlib/Instructions/README.md" property="og:url">
<meta content="summary" property="twitter:card">
<meta content="Homework/05-Matplotlib/Instructions/README.md · master · GW-Coding-Boot-Camp / 10-16-2017-GW-Arlington-Class-Repository-DATA" property="twitter:title">
<meta content="GitLab Community Edition" property="twitter:description">
<meta content="http://gw.bootcampcontent.com/assets/gitlab_logo-7ae504fe4f68fdebb3c2034e36621930cd36ea87924c11ff65dbcb8ed50dca58.png" property="twitter:image">

<title>Homework/05-Matplotlib/Instructions/README.md · master · GW-Coding-Boot-Camp / 10-16-2017-GW-Arlington-Class-Repository-DATA · GitLab</title>
<meta content="GitLab Community Edition" name="description">
<link rel="shortcut icon" type="image/x-icon" href="/assets/favicon-075eba76312e8421991a0c1f89a89ee81678bcde72319dd3e8047e2a47cd3a42.ico" />
<link rel="stylesheet" media="all" href="/assets/application-d165f12070137b3b436a61f947940b2ced66ac0acb1c4b61ee70daf598ef42ae.css" />
<link rel="stylesheet" media="print" href="/assets/print-68eed6d8135d858318821e790e25da27b2b4b9b8dbb1993fa6765d8e2e3e16ee.css" />
<script src="/assets/application-025f6d7648c857a731cbfd24fefde37e42f1613525a8d15b3b2a591e7df17620.js"></script>
<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="llYRQTlHnkRoI/rgc2/Zv9wil+HO7UiPjrm2z+gV1somY2tX3Yc3PZxirLaryAA+oMtrAEOmxiCc3zGLWan+UQ==" />
<meta content="origin-when-cross-origin" name="referrer">
<meta content="width=device-width, initial-scale=1, maximum-scale=1" name="viewport">
<meta content="#474D57" name="theme-color">
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-iphone-5a9cee0e8a51212e70b90c87c12f382c428870c0ff67d1eb034d884b78d2dae7.png" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-ipad-a6eec6aeb9da138e507593b464fdac213047e49d3093fc30e90d9a995df83ba3.png" sizes="76x76" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-iphone-retina-72e2aadf86513a56e050e7f0f2355deaa19cc17ed97bbe5147847f2748e5a3e3.png" sizes="120x120" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-ipad-retina-8ebe416f5313483d9c1bc772b5bbe03ecad52a54eba443e5215a22caed2a16a2.png" sizes="152x152" />
<link color="rgb(226, 67, 41)" href="/assets/logo-d36b5212042cebc89b96df4bf6ac24e43db316143e89926c0db839ff694d2de4.svg" rel="mask-icon">
<meta content="/assets/msapplication-tile-1196ec67452f618d39cdd85e2e3a542f76574c071051ae7effbfde01710eb17d.png" name="msapplication-TileImage">
<meta content="#30353E" name="msapplication-TileColor">




<style>
  [data-user-is] {
    display: none !important;
  }
  
  [data-user-is="270"] {
    display: block !important;
  }
  
  [data-user-is="270"][data-display="inline"] {
    display: inline !important;
  }
  
  [data-user-is-not] {
    display: block !important;
  }
  
  [data-user-is-not][data-display="inline"] {
    display: inline !important;
  }
  
  [data-user-is-not="270"] {
    display: none !important;
  }
</style>

</head>

<body class="ui_charcoal" data-group="" data-page="projects:blob:show" data-project="10-16-2017-GW-Arlington-Class-Repository-DATA">
<script>
//<![CDATA[
window.gon={};gon.api_version="v3";gon.default_avatar_url="http:\/\/gw.bootcampcontent.com\/assets\/no_avatar-849f9c04a3a0d0cea2424ae97b27447dc64a7dbfae83c036c45b403392f0e8ba.png";gon.max_file_size=10;gon.relative_url_root="";gon.shortcuts_path="\/help\/shortcuts";gon.user_color_scheme="white";gon.award_menu_url="\/emojis";gon.current_user_id=270;
//]]>
</script>
<script>
  window.project_uploads_path = "/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/uploads";
  window.preview_markdown_path = "/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/preview_markdown";
</script>

<header class="navbar navbar-fixed-top navbar-gitlab with-horizontal-nav">
<div class="container-fluid">
<div class="header-content">
<button aria-label="Toggle global navigation" class="side-nav-toggle" type="button">
<span class="sr-only">Toggle navigation</span>
<i class="fa fa-bars"></i>
</button>
<button class="navbar-toggle" type="button">
<span class="sr-only">Toggle navigation</span>
<i class="fa fa-ellipsis-v"></i>
</button>
<div class="navbar-collapse collapse">
<ul class="nav navbar-nav">
<li class="hidden-sm hidden-xs">
<div class="has-location-badge search search-form">
<form class="navbar-form" action="/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" /><div class="search-input-container">
<div class="location-badge">This project</div>
<div class="search-input-wrap">
<div class="dropdown" data-url="/search/autocomplete">
<input type="search" name="search" id="search" placeholder="Search" class="search-input dropdown-menu-toggle js-search-dashboard-options" spellcheck="false" tabindex="1" autocomplete="off" data-toggle="dropdown" data-issues-path="http://gw.bootcampcontent.com/dashboard/issues" data-mr-path="http://gw.bootcampcontent.com/dashboard/merge_requests" />
<div class="dropdown-menu dropdown-select">
<div class="dropdown-content"><ul>
<li>
<a class="is-focused dropdown-menu-empty-link">
Loading...
</a>
</li>
</ul>
</div><div class="dropdown-loading"><i class="fa fa-spinner fa-spin"></i></div>
</div>
<i class="search-icon"></i>
<i class="clear-icon js-clear-input"></i>
</div>
</div>
</div>
<input type="hidden" name="group_id" id="group_id" class="js-search-group-options" />
<input type="hidden" name="project_id" id="search_project_id" value="90" class="js-search-project-options" data-project-path="10-16-2017-GW-Arlington-Class-Repository-DATA" data-name="10-16-2017-GW-Arlington-Class-Repository-DATA" data-issues-path="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/issues" data-mr-path="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/merge_requests" />
<input type="hidden" name="search_code" id="search_code" value="true" />
<input type="hidden" name="repository_ref" id="repository_ref" value="master" />

<div class="search-autocomplete-opts hide" data-autocomplete-path="/search/autocomplete" data-autocomplete-project-id="90" data-autocomplete-project-ref="master"></div>
</form></div>

</li>
<li class="visible-sm visible-xs">
<a title="Search" aria-label="Search" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/search"><i class="fa fa-search"></i>
</a></li>
<li>
<a title="Todos" aria-label="Todos" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/dashboard/todos"><i class="fa fa-bell fa-fw"></i>
<span class="badge hidden todos-pending-count">
0
</span>
</a></li>
<li>
<a title="New project" aria-label="New project" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/projects/new"><i class="fa fa-plus fa-fw"></i>
</a></li>
<li class="header-user dropdown">
<a class="header-user-dropdown-toggle" data-toggle="dropdown" href="/roduok"><img width="26" height="26" class="header-user-avatar" src="http://www.gravatar.com/avatar/39f15a9ae07ddc504f147d0ed2b2dccf?s=52&amp;d=identicon" alt="39f15a9ae07ddc504f147d0ed2b2dccf?s=52&amp;d=identicon" />
<i class="fa fa-caret-down"></i>
</a><div class="dropdown-menu-nav dropdown-menu-align-right">
<ul>
<li>
<a class="profile-link" aria-label="Profile" data-user="roduok" href="/roduok">Profile</a>
</li>
<li>
<a aria-label="Profile Settings" href="/profile">Profile Settings</a>
</li>
<li class="divider"></li>
<li>
<a class="sign-out-link" aria-label="Sign out" rel="nofollow" data-method="delete" href="/users/sign_out">Sign out</a>
</li>
</ul>
</div>
</li>
</ul>
</div>
<h1 class="title"><a href="/GW-Coding-Boot-Camp">GW-Coding-Boot-Camp</a> / <a class="project-item-select-holder" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA">10-16-2017-GW-Arlington-Class-Repository-DATA</a><button name="button" type="button" class="dropdown-toggle-caret js-projects-dropdown-toggle" aria-label="Toggle switch project dropdown" data-target=".js-dropdown-menu-projects" data-toggle="dropdown"><i class="fa fa-chevron-down"></i></button></h1>
<div class="header-logo">
<a class="home" title="Dashboard" id="logo" href="/"><svg width="36" height="36" class="tanuki-logo">
  <path class="tanuki-shape tanuki-left-ear" fill="#e24329" d="M2 14l9.38 9v-9l-4-12.28c-.205-.632-1.176-.632-1.38 0z"/>
  <path class="tanuki-shape tanuki-right-ear" fill="#e24329" d="M34 14l-9.38 9v-9l4-12.28c.205-.632 1.176-.632 1.38 0z"/>
  <path class="tanuki-shape tanuki-nose" fill="#e24329" d="M18,34.38 3,14 33,14 Z"/>
  <path class="tanuki-shape tanuki-left-eye" fill="#fc6d26" d="M18,34.38 11.38,14 2,14 6,25Z"/>
  <path class="tanuki-shape tanuki-right-eye" fill="#fc6d26" d="M18,34.38 24.62,14 34,14 30,25Z"/>
  <path class="tanuki-shape tanuki-left-cheek" fill="#fca326" d="M2 14L.1 20.16c-.18.565 0 1.2.5 1.56l17.42 12.66z"/>
  <path class="tanuki-shape tanuki-right-cheek" fill="#fca326" d="M34 14l1.9 6.16c.18.565 0 1.2-.5 1.56L18 34.38z"/>
</svg>

</a></div>
<div class="js-dropdown-menu-projects">
<div class="dropdown-menu dropdown-select dropdown-menu-projects">
<div class="dropdown-title"><span>Go to a project</span><button class="dropdown-title-button dropdown-menu-close" aria-label="Close" type="button"><i class="fa fa-times dropdown-menu-close-icon"></i></button></div>
<div class="dropdown-input"><input type="search" id="" class="dropdown-input-field" placeholder="Search your projects" autocomplete="off" /><i class="fa fa-search dropdown-input-search"></i><i role="button" class="fa fa-times dropdown-input-clear js-dropdown-input-clear"></i></div>
<div class="dropdown-content"></div>
<div class="dropdown-loading"><i class="fa fa-spinner fa-spin"></i></div>
</div>
</div>

</div>
</div>
</header>

<script>
  var findFileURL = "/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/find_file/master";
</script>

<div class="page-with-sidebar">
<div class="sidebar-wrapper nicescroll">
<div class="sidebar-action-buttons">
<div class="nav-header-btn toggle-nav-collapse" title="Open/Close">
<span class="sr-only">Toggle navigation</span>
<i class="fa fa-bars"></i>
</div>
<div class="nav-header-btn pin-nav-btn has-tooltip  js-nav-pin" data-container="body" data-placement="right" title="Pin Navigation">
<span class="sr-only">Toggle navigation pinning</span>
<i class="fa fa-fw fa-thumb-tack"></i>
</div>
</div>
<ul class="nav nav-sidebar">
<li class="active home"><a title="Projects" class="dashboard-shortcuts-projects" href="/dashboard/projects"><span>
Projects
</span>
</a></li><li class=""><a title="Todos" href="/dashboard/todos"><span>
Todos
<span class="count">0</span>
</span>
</a></li><li class=""><a class="dashboard-shortcuts-activity" title="Activity" href="/dashboard/activity"><span>
Activity
</span>
</a></li><li class=""><a title="Groups" href="/dashboard/groups"><span>
Groups
</span>
</a></li><li class=""><a title="Milestones" href="/dashboard/milestones"><span>
Milestones
</span>
</a></li><li class=""><a title="Issues" class="dashboard-shortcuts-issues" href="/dashboard/issues?assignee_id=270"><span>
Issues
<span class="count">0</span>
</span>
</a></li><li class=""><a title="Merge Requests" class="dashboard-shortcuts-merge_requests" href="/dashboard/merge_requests?assignee_id=270"><span>
Merge Requests
<span class="count">0</span>
</span>
</a></li><li class=""><a title="Snippets" href="/dashboard/snippets"><span>
Snippets
</span>
</a></li><li class=""><a title="Help" href="/help"><span>
Help
</span>
</a></li><li class=""><a title="Profile Settings" data-placement="bottom" href="/profile"><span>
Profile Settings
</span>
</a></li></ul>

</div>
<div class="layout-nav">
<div class="container-fluid">
<div class="controls">
<div class="dropdown project-settings-dropdown">
<a class="dropdown-new btn btn-default" data-toggle="dropdown" href="#" id="project-settings-button">
<i class="fa fa-cog"></i>
<i class="fa fa-caret-down"></i>
</a>
<ul class="dropdown-menu dropdown-menu-align-right">
<li class=""><a title="Members" class="team-tab tab" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/project_members"><span>
Members
</span>
</a></li>
<li class="divider"></li>
<li>
<a data-confirm="Are you sure you want to leave the &quot;GW-Coding-Boot-Camp / 10-16-2017-GW-Arlington-Class-Repository-DATA&quot; project?" title="Leave project" rel="nofollow" data-method="delete" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/project_members/leave">Leave Project
</a></li>
</ul>
</div>
</div>
<div class="nav-control scrolling-tabs-container">
<div class="fade-left">
<i class="fa fa-angle-left"></i>
</div>
<div class="fade-right">
<i class="fa fa-angle-right"></i>
</div>
<ul class="nav-links scrolling-tabs">
<li class="home"><a title="Project" class="shortcuts-project" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA"><span>
Project
</span>
</a></li><li class=""><a title="Activity" class="shortcuts-project-activity" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/activity"><span>
Activity
</span>
</a></li><li class="active"><a title="Repository" class="shortcuts-tree" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/tree/master"><span>
Repository
</span>
</a></li><li class=""><a title="Pipelines" class="shortcuts-pipelines" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/pipelines"><span>
Pipelines
</span>
</a></li><li class=""><a title="Graphs" class="shortcuts-graphs" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/graphs/master"><span>
Graphs
</span>
</a></li><li class=""><a title="Issues" class="shortcuts-issues" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/issues"><span>
Issues
<span class="badge count issue_counter">0</span>
</span>
</a></li><li class=""><a title="Merge Requests" class="shortcuts-merge_requests" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/merge_requests"><span>
Merge Requests
<span class="badge count merge_counter">0</span>
</span>
</a></li><li class=""><a title="Wiki" class="shortcuts-wiki" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/wikis/home"><span>
Wiki
</span>
</a></li><li class=""><a title="Snippets" class="shortcuts-snippets" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/snippets"><span>
Snippets
</span>
</a></li><li class="hidden">
<a title="Network" class="shortcuts-network" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/network/master">Network
</a></li>
<li class="hidden">
<a class="shortcuts-new-issue" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/issues/new">Create a new issue
</a></li>
<li class="hidden">
<a title="Commits" class="shortcuts-commits" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/commits/master">Commits
</a></li>
<li class="hidden">
<a title="Issue Boards" class="shortcuts-issue-boards" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/boards">Issue Boards</a>
</li>
</ul>
</div>

</div>
</div>
<div class="content-wrapper page-with-layout-nav">
<div class="scrolling-tabs-container sub-nav-scroll">
<div class="fade-left">
<i class="fa fa-angle-left"></i>
</div>
<div class="fade-right">
<i class="fa fa-angle-right"></i>
</div>

<div class="nav-links sub-nav scrolling-tabs">
<ul class="container-fluid container-limited">
<li class="active"><a href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/tree/master">Files
</a></li><li class=""><a href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/commits/master">Commits
</a></li><li class=""><a href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/network/master">Network
</a></li><li class=""><a href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/compare?from=master&amp;to=master">Compare
</a></li><li class=""><a href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/branches">Branches
</a></li><li class=""><a href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/tags">Tags
</a></li></ul>
</div>
</div>



<div class="flash-container flash-container-page">
</div>


<div class=" ">
<div class="content">

<div class="container-fluid container-limited">

<div class="tree-holder" id="tree-holder">
<div class="nav-block">
<div class="tree-ref-holder">
<form class="project-refs-form" action="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/refs/switch" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="destination" id="destination" value="blob" />
<input type="hidden" name="path" id="path" value="Homework/05-Matplotlib/Instructions/README.md" />
<div class="dropdown">
<button class="dropdown-menu-toggle js-project-refs-dropdown" type="button" data-toggle="dropdown" data-selected="master" data-ref="master" data-refs-url="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/refs" data-field-name="ref" data-submit-form-on-click="true"><span class="dropdown-toggle-text ">master</span><i class="fa fa-chevron-down"></i></button>
<div class="dropdown-menu dropdown-menu-selectable">
<div class="dropdown-title"><span>Switch branch/tag</span><button class="dropdown-title-button dropdown-menu-close" aria-label="Close" type="button"><i class="fa fa-times dropdown-menu-close-icon"></i></button></div>
<div class="dropdown-input"><input type="search" id="" class="dropdown-input-field" placeholder="Search branches and tags" autocomplete="off" /><i class="fa fa-search dropdown-input-search"></i><i role="button" class="fa fa-times dropdown-input-clear js-dropdown-input-clear"></i></div>
<div class="dropdown-content"></div>
<div class="dropdown-loading"><i class="fa fa-spinner fa-spin"></i></div>
</div>
</div>
</form>
</div>
<ul class="breadcrumb repo-breadcrumb">
<li>
<a href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/tree/master">10-16-2017-GW-Arlington-Class-Repository-DATA
</a></li>
<li>
<a href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/tree/master/Homework">Homework</a>
</li>
<li>
<a href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/tree/master/Homework/05-Matplotlib">05-Matplotlib</a>
</li>
<li>
<a href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/tree/master/Homework/05-Matplotlib/Instructions">Instructions</a>
</li>
<li>
<a href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/blob/master/Homework/05-Matplotlib/Instructions/README.md"><strong>
README.md
</strong>
</a></li>
</ul>
</div>
<ul class="blob-commit-info hidden-xs">
<li class="commit js-toggle-container" id="commit-14280cb9">
<a href="/benfuja"><img class="avatar has-tooltip s36 hidden-xs" alt="Ben Fuja&#39;s avatar" title="Ben Fuja" data-container="body" src="http://www.gravatar.com/avatar/bbc29233cab3c2f4d4bd6e6f74d851d2?s=72&amp;d=identicon" /></a>
<div class="commit-info-block">
<div class="commit-row-title">
<span class="item-title">
<a class="commit-row-message" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/commit/14280cb9a849708d4dcdc3c8dff49b2802d42c2b">Added matplotlib homework</a>
<span class="commit-row-message visible-xs-inline">
&middot;
14280cb9
</span>
</span>
<div class="commit-actions hidden-xs">
<button class="btn btn-clipboard btn-transparent" data-toggle="tooltip" data-placement="bottom" data-container="body" data-clipboard-text="14280cb9a849708d4dcdc3c8dff49b2802d42c2b" type="button" title="Copy to Clipboard"><i class="fa fa-clipboard"></i></button>
<a class="commit-short-id btn btn-transparent" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/commit/14280cb9a849708d4dcdc3c8dff49b2802d42c2b">14280cb9</a>

</div>
</div>
<div class="commit-row-info">
<a class="commit-author-link has-tooltip" title="benfuja@gmail.com" href="/benfuja">Ben Fuja</a>
authored
<time class="js-timeago js-timeago-pending" datetime="2017-11-16T02:21:10Z" title="Nov 16, 2017 2:21am" data-toggle="tooltip" data-placement="top" data-container="body">2017-11-15 21:21:10 -0500</time><script>
//<![CDATA[
$('.js-timeago-pending').removeClass('js-timeago-pending').timeago()
//]]>
</script>
</div>
</div>
</li>

</ul>
<div class="blob-content-holder" id="blob-content-holder">
<article class="file-holder">
<div class="file-title">
<i class="fa fa-file-text-o fa-fw"></i>
<strong>
README.md
</strong>
<small>
7.26 KB
</small>
<div class="file-actions hidden-xs">
<div class="btn-group tree-btn-group">
<a class="btn btn-sm" target="_blank" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/raw/master/Homework/05-Matplotlib/Instructions/README.md">Raw</a>
<a class="btn btn-sm" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/blame/master/Homework/05-Matplotlib/Instructions/README.md">Blame</a>
<a class="btn btn-sm" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/commits/master/Homework/05-Matplotlib/Instructions/README.md">History</a>
<a class="btn btn-sm" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/blob/6e2c20f384b01b29b2f48638d37607f25a7e2495/Homework/05-Matplotlib/Instructions/README.md">Permalink</a>
</div>
<div class="btn-group" role="group">
<a class="btn btn-sm" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/edit/master/Homework/05-Matplotlib/Instructions/README.md">Edit</a>
<button name="button" type="submit" class="btn btn-default" data-target="#modal-upload-blob" data-toggle="modal">Replace</button>
<button name="button" type="submit" class="btn btn-remove" data-target="#modal-remove-blob" data-toggle="modal">Delete</button>
</div>

</div>
</div>
<div class="file-content wiki">
<h2 dir="auto">&#x000A;<a id="unit-5-assignment-the-power-of-plots" class="anchor" href="#unit-5-assignment-the-power-of-plots" aria-hidden="true"></a>Unit 5 | Assignment - The Power of Plots</h2>&#x000A;&#x000A;<h2 dir="auto">&#x000A;<a id="background" class="anchor" href="#background" aria-hidden="true"></a>Background</h2>&#x000A;&#x000A;<p dir="auto">What good is data without a good plot to tell the story?</p>&#x000A;&#x000A;<p dir="auto">So, let's take what you've learned about Python Matplotlib and apply it to some real-world situations. For this assignment, you'll need to complete <strong>1 of 2</strong> Data Challenges. As always, it's your choice which you complete. <em>Perhaps</em>, choose the one most relevant to your future career.</p>&#x000A;&#x000A;<h2 dir="auto">&#x000A;<a id="option-1-pyber" class="anchor" href="#option-1-pyber" aria-hidden="true"></a>Option 1: Pyber</h2>&#x000A;&#x000A;<p dir="auto"></p><div class="image-container"><a class="no-attachment-icon" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/raw/master/Homework/05-Matplotlib/Instructions/Images/Ride.png" target="_blank"><img src="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/raw/master/Homework/05-Matplotlib/Instructions/Images/Ride.png" alt="Ride"></a></div>&#x000A;&#x000A;<p dir="auto">The ride sharing bonanza continues! Seeing the success of notable players like Uber and Lyft, you've decided to join a fledgling ride sharing company of your own. In your latest capacity, you'll be acting as Chief Data Strategist for the company. In this role, you'll be expected to offer data-backed guidance on new opportunities for market differentiation.</p>&#x000A;&#x000A;<p dir="auto">You've since been given access to the company's complete recordset of rides. This contains information about every active driver and historic ride, including details like city, driver count, individual fares, and city type.</p>&#x000A;&#x000A;<p dir="auto">Your objective is to build a <a href="https://en.wikipedia.org/wiki/Bubble_chart" rel="nofollow noreferrer" target="_blank">Bubble Plot</a> that showcases the relationship between four key variables:</p>&#x000A;&#x000A;<ul dir="auto">&#x000A;<li>Average Fare ($) Per City</li>&#x000A;<li>Total Number of Rides Per City</li>&#x000A;<li>Total Number of Drivers Per City</li>&#x000A;<li>City Type (Urban, Suburban, Rural)</li>&#x000A;</ul>&#x000A;&#x000A;<p dir="auto">In addition, you will be expected to produce the following three pie charts:</p>&#x000A;&#x000A;<ul dir="auto">&#x000A;<li>% of Total Fares by City Type</li>&#x000A;<li>% of Total Rides by City Type</li>&#x000A;<li>% of Total Drivers by City Type</li>&#x000A;</ul>&#x000A;&#x000A;<p dir="auto">As final considerations:</p>&#x000A;&#x000A;<ul dir="auto">&#x000A;<li>You must use the Pandas Library and the Jupyter Notebook.</li>&#x000A;<li>You must use the Matplotlib and Seaborn libraries.</li>&#x000A;<li>You must include a written description of three observable trends based on the data.</li>&#x000A;<li>You must use proper labeling of your plots, including aspects like: Plot Titles, Axes Labels, Legend Labels, Wedge Percentages, and Wedge Labels.</li>&#x000A;<li>Remember when making your plots to consider aesthetics!&#x000A;&#x000A;<ul>&#x000A;<li>You must stick to the Pyber color scheme (Gold, Light Sky Blue, and Light Coral) in producing your plot and pie charts.</li>&#x000A;<li>When making your Bubble Plot, experiment with effects like <code>alpha</code>, <code>edgecolor</code>, and <code>linewidths</code>.</li>&#x000A;<li>When making your Pie Chart, experiment with effects like <code>shadow</code>, <code>startangle</code>, and <code>explosion</code>.</li>&#x000A;</ul>&#x000A;</li>&#x000A;<li>You must include an exported markdown version of your Notebook called  <code>README.md</code> in your GitHub repository.</li>&#x000A;<li>See <a href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/blob/master/Homework/05-Matplotlib/Instructions/Pyber/Pyber_Example.pdf">Example Solution</a> for a reference on expected format.</li>&#x000A;</ul>&#x000A;&#x000A;<h2 dir="auto">&#x000A;<a id="option-2-pymaceuticals-inc" class="anchor" href="#option-2-pymaceuticals-inc" aria-hidden="true"></a>Option 2: Pymaceuticals Inc</h2>&#x000A;&#x000A;<p dir="auto"></p><div class="image-container"><a class="no-attachment-icon" href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/raw/master/Homework/05-Matplotlib/Instructions/Images/Laboratory.jpg" target="_blank"><img src="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/raw/master/Homework/05-Matplotlib/Instructions/Images/Laboratory.jpg" alt="Laboratory"></a></div>&#x000A;&#x000A;<p dir="auto">While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've since joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego, CA. Pymaceuticals specializes in drug-based, anti-cancer pharmaceuticals. In their most recent efforts, they've since begun screening for potential treatments to squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.</p>&#x000A;&#x000A;<p dir="auto">As their Chief Data Analyst, you've been given access to the complete data from their most recent animal study. In this study, 250 mice were treated through a variety of drug regimes over the course of 45 days. Their physiological responses were then monitored over the course of that time. Your objective is to analyze the data to show how four treatments (Capomulin, Infubinol, Ketapril, and Placebo) compare.</p>&#x000A;&#x000A;<p dir="auto">To do this you are tasked with:</p>&#x000A;&#x000A;<ul dir="auto">&#x000A;<li>Creating a scatter plot that shows how the tumor volume changes over time for each treatment.</li>&#x000A;<li>Creating a scatter plot that shows how the number of <a href="https://en.wikipedia.org/wiki/Metastasis" rel="nofollow noreferrer" target="_blank">metastatic</a> (cancer spreading) sites changes over time for each treatment.</li>&#x000A;<li>Creating a scatter plot that shows the number of mice still alive through the course of treatment (Survival Rate)</li>&#x000A;<li>Creating a bar graph that compares the total % tumor volume change for each drug across the full 45 days.</li>&#x000A;</ul>&#x000A;&#x000A;<p dir="auto">As final considerations:</p>&#x000A;&#x000A;<ul dir="auto">&#x000A;<li>You must use the Pandas Library and the Jupyter Notebook.</li>&#x000A;<li>You must use the Matplotlib and Seaborn libraries.</li>&#x000A;<li>You must include a written description of three observable trends based on the data.</li>&#x000A;<li>You must use proper labeling of your plots, including aspects like: Plot Titles, Axes Labels, Legend Labels, X and Y Axis Limits, etc.</li>&#x000A;<li>Your scatter plots must include <a href="https://en.wikipedia.org/wiki/Error_bar" rel="nofollow noreferrer" target="_blank">error bars</a>. This will allow the company to account for variability between mice. You may want to look into <a href="http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.sem.html" rel="nofollow noreferrer" target="_blank"><code>pandas.DataFrame.sem</code></a> for ideas on how to calculate this.</li>&#x000A;<li>Remember when making your plots to consider aesthetics!&#x000A;&#x000A;<ul>&#x000A;<li>Your legends should not be overlaid on top of any data.</li>&#x000A;<li>Your bar graph should indicate tumor growth as red and tumor reduction as green.&#x000A;It should also include a label with the percentage change for each bar. You may want to consult this <a href="http://composition.al/blog/2015/11/29/a-better-way-to-add-labels-to-bar-charts-with-matplotlib/" rel="nofollow noreferrer" target="_blank">tutorial</a> for relevant code snippets.</li>&#x000A;</ul>&#x000A;</li>&#x000A;<li>You must include an exported markdown version of your Notebook called  <code>README.md</code> in your GitHub repository.</li>&#x000A;<li>See <a href="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/blob/master/Homework/05-Matplotlib/Instructions/Pymaceuticals/Pymaceuticals_Example.pdf">Example Solution</a> for a reference on expected format. (Note: For this example, you are not required to match the tables or data frames included. Your only goal is to build the scatter plots and bar graphs. Consider the tables to be potential clues, but feel free to approach this problem, however, you like.)</li>&#x000A;</ul>&#x000A;&#x000A;<h2 dir="auto">&#x000A;<a id="hints-and-considerations" class="anchor" href="#hints-and-considerations" aria-hidden="true"></a>Hints and Considerations</h2>&#x000A;&#x000A;<ul dir="auto">&#x000A;<li><p>Be warned: These are very challenging tasks. Be patient with yourself as you trudge through these problems. They will take time and there is no shame in fumbling along the way. Data visualization is equal parts exploration, equal parts resolution.</p></li>&#x000A;<li><p>Between these two exercises, the Pymaceuticals one is significantly more challenging. So choose that one only if you feel somewhat comfortable with the material covered so far. The Pymaceuticals example <em>will</em> require you to research a good bit on your own for hacked solutions to problems you'll experience along the way. If you end up choosing this exercise, feel encouraged to constantly refer back to Stack Overflow and the Pandas Documentation. These are needed tools in every data analyst's arsenl.</p></li>&#x000A;<li><p>Don't get bogged down in small details. Always focus on the big picture. If you can't figure out how to get a label to show up correctly, come back to it. Focus on getting the core skeleton of your notebook complete. You can always re-visit old problems.</p></li>&#x000A;<li><p>Remember: There are many ways to skin a cat, and similarly there are many ways to approach a data problem. The key throughout, however, is to break up your task into micro tasks. Try answering questions like: "How does my Data Frame need to be structured for me to have the right X and Y axis?" "How do I build a basic scatter plot?" "How do I add a label to that scatter plot?" "Where would the labels for that scatter plot come from?". Again! Don't let the magnitude of a programming task scare you off. Ultimately, every programming problem boils down to a handful of smaller, bite-sized tasks.</p></li>&#x000A;<li><p>Get help when you need it! There is never any shame in asking. But as always, ask a <em>specific</em> question. You'll never get a great answer to: "I'm lost." Good luck!</p></li>&#x000A;</ul>&#x000A;&#x000A;<h2 dir="auto">&#x000A;<a id="copyright" class="anchor" href="#copyright" aria-hidden="true"></a>Copyright</h2>&#x000A;&#x000A;<p dir="auto">Coding Boot Camp (C) 2016. All Rights Reserved.</p>
</div>

</article>
</div>

</div>
<div class="modal" id="modal-remove-blob">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<a class="close" data-dismiss="modal" href="#">×</a>
<h3 class="page-title">Delete README.md</h3>
</div>
<div class="modal-body">
<form class="form-horizontal js-replace-blob-form js-quick-submit js-requires-input" action="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/blob/master/Homework/05-Matplotlib/Instructions/README.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="delete" /><input type="hidden" name="authenticity_token" value="XtLtACpdialJpQUJvIL7UiWF6aVOitgIFgv0PZyeb3/u55cWzp0g0L3kU19kJSLTWWwVRMPBVqcEbXN5LSJH5A==" /><div class="form-group commit_message-group">
<label class="control-label" for="commit_message-9bb78768992c73a3f775b4b1c9ad33b1">Commit message
</label><div class="col-sm-10">
<div class="commit-message-container">
<div class="max-width-marker"></div>
<textarea name="commit_message" id="commit_message-9bb78768992c73a3f775b4b1c9ad33b1" class="form-control js-commit-message" placeholder="Delete README.md" required="required" rows="3">
Delete README.md</textarea>
</div>
</div>
</div>

<div class="form-group branch">
<label class="control-label" for="target_branch">Target branch</label>
<div class="col-sm-10">
<input type="text" name="target_branch" id="target_branch" value="patch-5" required="required" class="form-control js-target-branch" />
<div class="js-create-merge-request-container">
<div class="checkbox">
<label for="create_merge_request-bbb49cf29683b46a8c979484aba4f3fa"><input type="checkbox" name="create_merge_request" id="create_merge_request-bbb49cf29683b46a8c979484aba4f3fa" value="1" class="js-create-merge-request" checked="checked" />
Start a <strong>new merge request</strong> with these changes
</label></div>
</div>
</div>
</div>
<input type="hidden" name="original_branch" id="original_branch" value="master" class="js-original-branch" />

<div class="form-group">
<div class="col-sm-offset-2 col-sm-10">
<button name="button" type="submit" class="btn btn-remove btn-remove-file">Delete file</button>
<a class="btn btn-cancel" data-dismiss="modal" href="#">Cancel</a>
</div>
</div>
</form></div>
</div>
</div>
</div>
<script>
  new NewCommitForm($('.js-replace-blob-form'))
</script>

<div class="modal" id="modal-upload-blob">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<a class="close" data-dismiss="modal" href="#">×</a>
<h3 class="page-title">Replace README.md</h3>
</div>
<div class="modal-body">
<form class="js-quick-submit js-upload-blob-form form-horizontal" action="/GW-Coding-Boot-Camp/10-16-2017-GW-Arlington-Class-Repository-DATA/update/master/Homework/05-Matplotlib/Instructions/README.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="EHQ11cvbQvwTWfnUOPicr+0hEJfAhMGxHY2lErGjwrGgQU/DLxvrhecYr4LgX0Uukcjsdk3PTx4P6yJWAB/qKg==" /><div class="dropzone">
<div class="dropzone-previews blob-upload-dropzone-previews">
<p class="dz-message light">
Attach a file by drag &amp; drop or
<a class="markdown-selector" href="#">click to upload</a>
</p>
</div>
</div>
<br>
<div class="alert alert-danger data dropzone-alerts" style="display:none"></div>
<div class="form-group commit_message-group">
<label class="control-label" for="commit_message-2a1d6ecbf29b992f1466353bb1af71aa">Commit message
</label><div class="col-sm-10">
<div class="commit-message-container">
<div class="max-width-marker"></div>
<textarea name="commit_message" id="commit_message-2a1d6ecbf29b992f1466353bb1af71aa" class="form-control js-commit-message" placeholder="Replace README.md" required="required" rows="3">
Replace README.md</textarea>
</div>
</div>
</div>

<div class="form-group branch">
<label class="control-label" for="target_branch">Target branch</label>
<div class="col-sm-10">
<input type="text" name="target_branch" id="target_branch" value="patch-5" required="required" class="form-control js-target-branch" />
<div class="js-create-merge-request-container">
<div class="checkbox">
<label for="create_merge_request-140f9fdcc05787b79f114379940bad80"><input type="checkbox" name="create_merge_request" id="create_merge_request-140f9fdcc05787b79f114379940bad80" value="1" class="js-create-merge-request" checked="checked" />
Start a <strong>new merge request</strong> with these changes
</label></div>
</div>
</div>
</div>
<input type="hidden" name="original_branch" id="original_branch" value="master" class="js-original-branch" />

<div class="form-actions">
<button name="button" type="submit" class="btn btn-small btn-create btn-upload-file" id="submit-all">Replace file</button>
<a class="btn btn-cancel" data-dismiss="modal" href="#">Cancel</a>
</div>
</form></div>
</div>
</div>
</div>
<script>
  disableButtonIfEmptyField($('.js-upload-blob-form').find('.js-commit-message'), '.btn-upload-file');
  new BlobFileDropzone($('.js-upload-blob-form'), 'put');
  new NewCommitForm($('.js-upload-blob-form'))
</script>

</div>

</div>
</div>
</div>
</div>



</body>
</html>

