function fnPagination(type,param){
	var oPage_number = document.getElementById("page_number");
	var page_number = parseInt(oPage_number.value);
	switch (type)
	{
	case 1://Next
		oPage_number.value = (page_number+1);
		break;
	case 2://Last
		oPage_number.value = param;
		break;
	case 3://Previous
		oPage_number.value = (page_number-1);
		break;
	case 4://First
		oPage_number.value = 1;
		break;
	case 5://Page size change
		oPage_number.value = 1;
		break;
	case 6://sort
		var oSortColumn = document.getElementById("sortColumn");
		var oSortOrder = document.getElementById("sortOrder");
		if(oSortColumn.value == param && oSortOrder.value != "DESC") 
			oSortOrder.value = "DESC";
		else oSortOrder.value = "ASC";
		oSortColumn.value = param;
		break;
	}
	
	document.paginationForm.submit();
}