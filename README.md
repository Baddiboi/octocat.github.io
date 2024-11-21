# octocat.github.io

div {
	margin: 10px 20px 30px 40px; 
	   /*-top(1) -right(2) -bottom(3) -left(4) 
	   á bæði við margin og padding */
	
	padding: 10px 20px; 
		/*top+bottom og left+right 
		á bæði við margin og padding */
	
	border: 5px solid #f0f; 
	        /*-weight, -style, -color */
	/* 7 gildi eru í border-style: solid, dotted, dashed, double, ridge, inset, outset,*/
	/*ath! að veja aðeins eitt gildi á border-style:*/
}

body {
    font-family: Helvetica, sans-serif; /* vafrinn velur Helvetica ef það er til, annars system font (sans-serif) */ 
    font-style: normal;      /* italic, obligue */
    font-weight: 500;     /* normal, bold, 100 - 900 */
    font-size: 1rem;          /* 16px, 1em, 100% */
    line-height: 1.5;         /* tekur mið af einingunni sem er á font-size */
}

/* hér er öllum stílum sópað saman í eina skipun "font:"*/
body {
    font:normal 500 1rem/1.5 Helvetica, sans-serif;
    /*font-style, -weight, -size/-lineheight -family */
}

