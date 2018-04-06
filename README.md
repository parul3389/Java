# Java

import java.util.concurrent.ArrayBlockingQueue;
import java.util.concurrent.BlockingQueue;
import java.util.concurrent.PriorityBlockingQueue;


public class BlockingQueueImpl {
	public static void main(String as[]) throws InterruptedException{
		
		// ArrayBlockingQueue - Queue with fixed elements
		BlockingQueue<String> abq = new ArrayBlockingQueue<String>(1);
		
		abq.put("a");
		//abq.put("a");
		// will wait for present items to be consumed
		System.out.println("inserted");
		abq.take();
		System.out.println("removed");
		abq.take();		
		System.out.println("End");
		
		// PriorityBlockingQueue - Queue can expand, and maintains priority using Comparable or Comaparator if provided
		BlockingQueue<String> pbq = new PriorityBlockingQueue<String>();
		
		
		
		
		
	}

}

