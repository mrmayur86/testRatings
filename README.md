# testRatings
Test for customer ratings

I have created a new bean 
	<bean id="mayureshCustomerReviewService" class="de.hybris.platform.customerreview.impl.MayureshCustomerReviewService" parent="abstractBusinessService" scope="tenant">
		<property name="customerReviewDao" ref="customerReviewDao"/>
		<property name="cussWords" value="idiot stupid monkey"/>
		<property name="rangeMinValue" value="2"/>
		<property name="rangeMaxValue" value="4"/>
	</bean>	  
and passed parameters as properties I can also pass parameters as config in de.hybris.platform.util.Config class but I don't have jar so cannot compile and verify
