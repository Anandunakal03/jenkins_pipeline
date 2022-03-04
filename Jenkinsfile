pipeline
{
	agent any
	{
		stages
		{
			Stage('Build')
			{
				steps
				{
					sh 'sleep 5; echo "This is Build stage"'
				}
			}
			Stage('Deploy')
			{
				steps
				{
					sh '''
						sleep 5
						echo "this is a Deploy stage"
					
					'''
				}
			}
			Stage('Test')
			{
				steps
				{
					sh '''
						sleep 5
						echo "this is a Test stage"
					
					'''
				}
			}
			Stage('My-stage')
			{
				steps
				{
					sh '''
						sleep 5
						echo "this is a My stage"
					
					'''
				}
			}
		}
	}

}