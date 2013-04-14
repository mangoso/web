/* import base CSS style */
@import 'default.css';


/* globals */
input[type=submit]:hover  { background: #313428; }

a, a:link, a:visited  { color: #2C445E; text-decoration: none; }
a:hover					{ color: #BF511F; }

/* header */
#header					{ background: #091E36; border-bottom: 5px solid #0f3158; }
.blog-description		{ font-size: 11px; color: #19508C; }

/* top menu */
#top-menu  { background: #061424; border-bottom: 1px solid #0C2845; }
#top-menu .sf-menu a  { color: #FFF; }
#top-menu .sf-menu ul li  { border: 1px solid #061321; }
#top-menu .sf-menu a:hover, #top-menu .sf-menu li:hover, #top-menu .sf-menu li.sfHover, #top-menu .sf-menu ul li  { color: #FFF; background: #103259; }
#top-menu .sf-menu ul a:hover, #top-menu .sf-menu ul li.sfHover, #top-menu .sf-menu ul li:hover { color: #103259; background: #FFF; }
#top-menu .sf-menu ul li.sfHover a.sf-with-ul { color: #103259; }

/* main navigation */
#nav  { background: #003773; min-width: 990px; }
#nav .sf-menu a  { color: #FFF; }
#nav .sf-menu ul li  { border: 1px solid #0F3158; }
#nav .sf-menu a:hover, #nav .sf-menu li:hover, #nav .sf-menu li.sfHover, #nav .sf-menu ul li  { background: #0F3158; color: #FFF; }
#nav .sf-menu ul a:hover, #nav .sf-menu ul li.sfHover, #nav .sf-menu ul li:hover { color: #0F3158; background: #FFF; }
#nav .sf-menu ul li.sfHover a.sf-with-ul { color: #0F3158; }

/* search bar */
.searchform  { border: 3px solid #19508C; }

/* sidebar */
.sidebar-read-more:link, .sidebar-read-more:visited	{ background: #091E36; }
.sidebar-read-more:hover  { background: #BF511F; }

.widgettitle  { background: #003773; color: #FFF; }
.widgettitle a  { color: #FFF; }

#bottom-content-1 .widgettitle, #bottom-content-2 .widgettitle  { color: #333; }

.multi-sidebar .tabs li	{ background: #144275; border: 1px solid #CCC; }				
.multi-sidebar .tabs .ui-tabs-selected a:link, .multi-sidebar .tabs .ui-tabs-selected a:visited	{ color: #37322F; }			

/* tapestries */
.posts-quick .quick-read-more a:hover, #commentlist .comment-controls a:hover, .navigation a:hover, .comments-navigation a:hover, .wp-pagenavi a:hover, .wp-pagenavi span.current, .comments-navigation span.current  { background: #003773; color: #FFF; }

.home-title				{ color: #091e36; }

/* single post */
.single .post .entry-comments, .single-post .entry-comments  { background-color: #091E36; display: inline-block; color: #FFF; }

.single-post-meta-field  { background: #091E36; display: block; border: 1px solid #0F3158; padding: 5px 10px; color: #FFF; font-weight: 700; }
.single-post-meta-value	 { border: 1px solid #CCC; padding: 5px 10px; background: #F0F0F0; display: block; }

/* author template */
.author-posts-title, .author-content h1, .archive-title { color: #091e36; }
